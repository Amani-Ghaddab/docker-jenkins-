pipeline {
    agent any

    stages {
       
	
        stage('Integration Test') {
		 steps {
                sh "${which docker} docker-compose -f docker-compose.yml up "
              
           	 }


            }
	
        
    }
}