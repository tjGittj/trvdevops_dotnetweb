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
          customWorkspace 'C:\\workspace\\trvdevops'
        }

      }
      steps {
        powershell 'pwd'
        powershell 'ls'
      }
    }
  }
}
