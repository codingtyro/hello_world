pipeline {
  agent any
  stages {
    stage('1') {
      steps {
        echo '22'
      }
    }

    stage('2') {
      steps {
        echo '11'
      }
    }

    stage('3') {
      steps {
        sleep 10
      }
    }

    stage('4') {
<<<<<<< HEAD
	steps {
	  echo 'hello,world'
     }
=======
      steps {
        bat(script: 'hello.bat', returnStatus: true)
      }
>>>>>>> 91d90e194daf67a436977d28b8e2a2a2c942e16f
    }

  }
}