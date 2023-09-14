pipeline {
  agent any
  stages {
    stage('Code Checkout') {
      steps {
        git 'https://github.com/Daedalus2001/Forex'
      }
    }

    stage('Logs') {
      steps {
        sh 'ls -la'
      }
    }

  }
}