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

    stage('Test') {
      steps {
        sleep 5
      }
    }

  }
}