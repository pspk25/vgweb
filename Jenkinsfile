pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh '/etc/passwd'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
