pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Cloning done automatically by Jenkins'
            }
        }

        stage('Git Info') {
            steps {
                bat 'git status'
                bat 'git log --oneline'
            }
        }

        stage('Build') {
            steps {
                bat 'echo Building project...'
            }
        }

        stage('Test') {
            steps {
                bat 'echo Testing project...'
            }
        }

        stage('Deploy') {
            steps {
                bat 'echo Deploying project...'
            }
        }
    }
}
