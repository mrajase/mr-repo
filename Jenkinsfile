pipeline {
    agent any
    stages {

      stage('Lint HTML') {
        steps {
          sh 'tidy -q -e *.html'
        }
      }

      stage('Upload to AWS') {
        steps {
          withAWS(region:'us-west-1',credentials:'mr-user') {
            s3Upload(pathStyleAccessEnabled:true, payloadSigningEnabled: true, file:'index.html', bucket:'mr-cicd')
          }
        }
      }

    }
}
