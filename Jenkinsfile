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
		echo “Multiline shell steps works too”
		sh '
			ls -lah
			date
		'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
