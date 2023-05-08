pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name s3bucket --template-body file://cloudformation.json --region 'eu-central-1'"
              }
             }
            }
            }