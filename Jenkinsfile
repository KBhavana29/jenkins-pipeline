pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            exec "aws cloudformation create-stack --stack-name s3bucket --template-body file://s3lifecycle.yml --region 'us-east-1'"
              }
             }
            }
            }
