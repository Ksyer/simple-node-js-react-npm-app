pipeline {
  agent {
    docker {
      image 'node:10'
      label 'huatree-node'
      args '-p 3000:3000' 
    }
  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install' 
      }
    }
  }
}
