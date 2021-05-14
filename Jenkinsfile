pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name jenkins-node2-stack --template-body file://my-test1.yml --region 'us-west-2'"    
              }
             }
            }
            }
