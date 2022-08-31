pipeline {
  agent none
  stages {
    stage('get') {
      steps {
        echo '22'
      }
    }

    stage('output') {
      steps {
        sh 'echo "hello"'
      }
    }

  }
  environment {
    fe = 'de'
  }
}