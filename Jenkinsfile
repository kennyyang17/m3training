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
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                sh 'ls'
                sh 'cp @ /usr/share/nginx/html'
                echo 'Deploying....'
            }
        }
    }
}
