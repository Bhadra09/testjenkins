pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
                sh "aws cloudformation create-stack --stack-name S3jenkinsgit --template-body file://gits3.yml --region us-east-1"
            }
        }
    }
}
