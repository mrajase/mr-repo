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
		sh '''    echo "Multiline test" 
		ls -lah  
		/bin/date
		'''
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
