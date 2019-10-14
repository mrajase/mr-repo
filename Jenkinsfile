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
		sh 'ls -lah'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
