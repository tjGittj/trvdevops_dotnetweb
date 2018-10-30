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
          label 'trvdevops001'
        }

      }
      steps {
        echo 'Hello'
      }
    }
  }
}