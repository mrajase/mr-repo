pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
		echo 'Hello World'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
		ls -lah
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
