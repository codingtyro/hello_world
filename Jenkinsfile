pipeline {
  agent none
  stages {
    stage('start') {
      parallel {
        stage('start') {
          steps {
            echo '55'
          }
        }

        stage('start1') {
          steps {
            echo '33'
          }
        }

      }
    }

    stage('output') {
      steps {
        sh 'echo this is my first program'
      }
    }

    stage('end') {
      steps {
        sleep 10
      }
    }

  }
}