pipeline {
    agent any

    stages {

        stage('Build Docker Image') {
            steps {
                bat 'docker build -t freestyle-demo:v1 .'
            }
        }

        stage('Show Images') {
            steps {
                bat 'docker images'
            }
        }

    }
}