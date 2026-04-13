pipeline {
    agent any

    stages {

        stage('Check Docker') {
            steps {
                bat 'docker --version'
            }
        }

        stage('Run Container') {
            steps {
                bat 'docker run hello-world'
            }
        }
    }
}
