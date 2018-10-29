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
        powershell(script: 'echo "This is Dev"', returnStatus: true, returnStdout: true)
      }
    }
  }
}