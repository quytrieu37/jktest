pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Deploying....'
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                sh 'whoami'
                sh 'ls -a'
                echo 'Deploying....'
            }
        }
    }
}