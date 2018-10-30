pipeline {
  agent {
    node {
      label 'trvdevops001'
    }

  }
  stages {
    stage('Build') {
      agent {
        node {
          label 'trvdevops001'
        }

      }
      steps {
        bat "dir"
      }
    }
  }
}
