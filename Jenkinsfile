pipeline {
  agent any
  stages {
    stage('1') {
      steps {
        echo 'Hello world!!'
      }
    }
 }
    stage('3') {
      parallel {
        stage('3') {
          steps {
            echo 'We are doing good!'
          }
        }
        stage('smth go wrong') {
          steps {
            echo 'We are doing bad =('
          }
        }
      }
    }
  }
  environment {
    Win7 = 'win7'
  }
}