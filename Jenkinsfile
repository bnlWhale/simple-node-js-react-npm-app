pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'node:8-alpine'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'sudo npm install'
        echo 'start to build'
      }
    }
  }
}
