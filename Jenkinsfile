pipeline {
  agent {
    docker {
      image 'esphome/esphome'
      args '--entrypoint /bin/bash -v Firmware:/config'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'Starting Build'
        sh '''ls -l
pwd'''
      }
    }
  }
}