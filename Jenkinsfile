pipeline {
    agent {
        docker { image 'python:3.12' }
    }

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/khadidjanemis5-wq/MonApp.git'
            }
        }

        stage('Run App') {
            steps {
                sh 'python app.py'
            }
        }
    }
}