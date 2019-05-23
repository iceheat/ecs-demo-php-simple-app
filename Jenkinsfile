pipeline {
  agent {
    docker {
      image 'php'
    }

  }
  stages {
    stage('test') {
      steps {
        sh 'docker ps'
      }
    }
  }
}