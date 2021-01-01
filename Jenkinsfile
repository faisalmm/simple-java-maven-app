pipeline {
  agent none
  stages {
    stage('CI') {
      steps {
        echo 'Welcome to Faisal\'s Pipeline'
      }
    }

    stage('run_cmd') {
      steps {
        sh '''#!/bin/bash

whoami
'''
      }
    }

  }
}