pipeline {
    agent {
	docker { image 'python:latest'}
    }

    stages {
        stage('Test for py') {
            steps {
                sh "pytest"
            }
        }
    }
}

