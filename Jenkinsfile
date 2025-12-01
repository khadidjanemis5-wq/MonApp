pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // هنا نحدّد الفرع صراحةً
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