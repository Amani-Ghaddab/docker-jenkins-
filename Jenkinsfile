pipeline {
    agent any

    stages {
       
	
        stage('Integration Test') {
		 steps {
                sh "docker-compose -f docker-compose.yml up --force-recreate --abort-on-container-exit"
              
           	 }


            }
	
        
    }
}