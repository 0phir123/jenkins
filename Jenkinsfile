pipeline {
    agent {
	docker { image 'python'}
    }

    stages {
        stage('Test for py') {
            steps {
                sh "pytest"
            }
        }
    }
}

