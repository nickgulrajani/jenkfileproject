pipeline {
    agent {
        docker { image 'node:14.3.0-buster' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
