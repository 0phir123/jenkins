pipeline {
    agent {
	docker { image 'python:latest'}
    }

    stages {
        
	stage('install pyetest')
	{
		sh "pip install pytest"
	}


	stage('Test for py') {
            steps {
                sh "pytest"
            }
        }
    }
}

