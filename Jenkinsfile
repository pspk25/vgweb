pipeline {
    agent any   
    environment {

    BITBUCKET_COMMON_CREDS = credentials('jenkins-bitbucket-common-creds')

    }
    stages {
        stage('Example stage 1') {
            steps {
                    sh 'printenv'
		    echo env.BITBUCKET_COMMON_CREDS
		    }
        }
        stage('Example stage 2') {
            steps {
                echo 'Hello' 
            }
        }
    }
}
