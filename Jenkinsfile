pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'id'
		sh 'pwd'
		sh 'hostname -i'
		sh 'ls -lart'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
