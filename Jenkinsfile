pipeline {
  agent {
    node {
      label 'node-label'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'cnpm install'
      }
    }
  }
}