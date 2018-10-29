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
        sh 'echo "This is Dev"'
      }
    }
  }
}