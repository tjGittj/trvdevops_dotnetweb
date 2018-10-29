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
        powershell(script: 'echo "This is Dev"', returnStatus: true, returnStdout: true)
      }
    }
  }
}