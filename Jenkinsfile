pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
                sh "aws cloudformation create-stack --stack-name EC2Instance --template-body file://createEC2.yaml"
            }
        }
    }
}
