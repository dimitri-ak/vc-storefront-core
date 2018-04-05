pipeline {
  agent {
    label "jenkins-core"
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
