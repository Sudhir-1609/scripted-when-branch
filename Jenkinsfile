node {
        if(env.BRANCH_NAME == 'main'){
			stage('Build Main') {
                echo 'Building master'
            }
        }
		
		if(env.BRANCH_NAME == 'dev'){
			stage('Build Dev') {            
                echo 'Building dev'
            }
        }
}
