pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                sh '''
                    echo "Running build stage"
                    pwd
                    ls
                '''
            }
        }
        stage ('test') {
            steps {
                sh '''
                whoami
                '''
            }
        }
    }
}
