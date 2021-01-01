pipeline {
  agent {
    docker {
      image 'busybox'
    }

  }
  stages {
    stage('CI') {
      steps {
        echo 'Welcome to Faisal\'s Pipeline'
      }
    }

    stage('run_cmd') {
      steps {
        sh '''whoami
'''
      }
    }

  }
}