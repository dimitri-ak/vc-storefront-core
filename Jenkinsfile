pipeline {
  agent {
    any
  }
  
  stages {
    stage('Checkout') {
      steps {
        container('core') {
          checkout scm
        }
      }
    }
  }
}
