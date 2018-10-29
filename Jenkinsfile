pipeline {
  agent {
    node {
      label 'trvdevops001'
    }

  }
  stages {
    stage('Dev') {
      steps {
        powershell(script: 'echo "This is Dev"', returnStatus: true, returnStdout: true)
      }
    }
  }
}