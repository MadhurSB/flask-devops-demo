pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Checking workspace...'
                sh 'pwd'
                sh 'ls -la'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Application'
            }
        }

        stage('Test') {
            steps {
                echo 'Running Tests'
                sh 'python3 --version'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment Successful'
            }
        }
    }
}
