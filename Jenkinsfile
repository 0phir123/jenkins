pipeline {
    agent {
	docker { image 'python:latest'}
    }

    stages {
        
	stage('fix permession'){
		
	     steps{
		    sh "sudo chmod 666 /var/run/docker.sock"
		}
	    
	}



	stage('Test for py') {
            steps {
                sh "pytest"
            }
        }
    }
}

