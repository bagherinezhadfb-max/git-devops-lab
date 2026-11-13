pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Source code checked out'
            }
        }

        stage('Build') {
            steps {
                echo 'Building application'
                sh 'cat app.txt'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests'
                sh 'test -f app.txt'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application'
            }
        }
    }
}
