pipeline {
    agent {
	docker { image 'python:latest'}
    }

    stages {
        
	stage('fix permession'){
		
	     steps{
		    sh "sudo chown root:jenkins /run/docker.sock"
		}
	    
	}



	stage('Test for py') {
            steps {
                sh "pytest"
            }
        }
    }
}

