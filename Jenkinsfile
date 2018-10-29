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
        powershell(script: 'echo "This is Dev"', returnStatus: true, returnStdout: true)
      }
    }
  }
}