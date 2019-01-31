pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'id'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
