pipeline {
    agent any

    stages {
       
	
        stage('Integration Test') {
		 steps {
                sh" sudo curl -L https://github.com/docker/compose/releases/download/1.25.3/run.sh -o /usr/local/bin/docker-compose"
                sh"sudo chmod +x /usr/local/bin/docker-compose"
                sh " docker-compose -f docker-compose.yml up "
              
           	 }


            }
	
        
    }
}