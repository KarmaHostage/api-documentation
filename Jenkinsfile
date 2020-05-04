pipeline {
    agent {
        docker {
            image 'node:10-alpine'
            args '-p 3000:3000'
        }
    }
    environment {
        CI = 'true'
    }
    stages {
        stage('Build') {
            steps {
                sh './ci/build.sh'
            }
        }
        stage('Build Docker') {
            steps {
                sh './ci/package.sh'
            }
        }
        stage('Push Docker') {
            steps {
                sh './ci/push.sh'
            }
        }
    }
}