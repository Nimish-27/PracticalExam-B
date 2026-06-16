pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Executing Checkout Stage'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Executing Build Stage'
                sh 'echo Building the application...'
            }
        }

        stage('Test') {
            steps {
                echo 'Executing Test Stage'
                sh 'echo Running tests...'
            }
        }
    }
}