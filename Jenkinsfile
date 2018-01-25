pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'uptime'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh 'date'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                sh 'who'
            }
        }
    }
}
