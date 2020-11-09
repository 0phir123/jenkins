pipeline {
    agent {
	docker { image 'python:latest'}
    }

    stages {
        

	stage('Test for py') {
            steps {
		
		sh "pip install pytest"
                sh "pytest"
            }
        }
    }
}

