pipeline {
  agent none
  stages {
    stage('get') {
      steps {
        echo '22'
      }
    }

    stage('echo') {
      steps {
        sh 'hello'
      }
    }

  }
  environment {
    fe = 'de'
  }
}