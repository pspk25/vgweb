pipeline {
    agent any   
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }
    stages {
        stage('Example stage 1') {
            steps {
                    sh 'printenv'
		    echo {env.AWS_ACCESS_KEY_ID}
            }
        }
        stage('Example stage 2') {
            steps {
                echo 'Hello' 
            }
        }
    }
}
