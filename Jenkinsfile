pipeline {
    agent any

    stages {
       
	
        stage('Integration Test') {
		 steps {
                sh "DOCKER_PATH=$(which docker) docker-compose -f docker-compose.yml up "
              
           	 }


            }
	
        
    }
}