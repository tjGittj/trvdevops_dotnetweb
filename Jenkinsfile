pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('Dev') {
      agent {
        node {
          label 'master'
        }

      }
      steps {
        echo 'Hello'
      }
    }
  }
}