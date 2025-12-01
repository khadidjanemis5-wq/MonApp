pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git 'https://github.com/khadidjanemis5-wq/MonApp.git'
      }
    }
    stage('Run App') {
      steps {
        sh 'python3 app.py'
      }
    }
  }
}