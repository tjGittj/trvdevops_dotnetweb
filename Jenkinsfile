pipeline {
  agent {
    node {
      label 'trvdevops001'
    }

  }
  stages {
    stage('Dev') {
      agent {
        node {
          label 'trvdevops001'
        }

      }
      steps {
        echo 'Hello'
      }
    }
  }
}