pipeline {
  agent {
    docker {
      image 'node'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'echo "hello"'
      }
    }
    stage('deploy') {
      steps {
        sh 'helm install nginx'
      }
    }
  }
}