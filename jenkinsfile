pipeline { 
  agent any 

  tools {
    nodejs 'Node'
  }

  stages {
    stage ('Checkout Code') {
      steps {
        checkout scm
      }
    }
    stage ('Install dependencies') {
      steps {
        sh "echo $PATH"
        sh "npm install"
      }
    }
  }
}
