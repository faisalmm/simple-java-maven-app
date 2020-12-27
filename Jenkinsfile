pipeline {
  agent {
    docker {
      image 'alpine'
    }

  }
  stages {
    stage('CI') {
      steps {
        echo 'Welcome to Faisal\'s Pipeline'
      }
    }

    stage('Whoami') {
      steps {
        sh '''w
whoami
w'''
      }
    }

  }
}