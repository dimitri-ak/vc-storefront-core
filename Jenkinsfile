pipeline {
  agent {
    label "any"
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
