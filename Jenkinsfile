pipeline { 
  agent any 

  tools {
    nodejs 'Node'
  }

  stages {
    stage ('Checkout Code') {
      steps {
        echo 'checkout scm'
      }
    }
    stage ('Install dependencies') {
      steps {
        sh "echo $PATH"
        sh "npm install"
      }
    }
    stage ('Build') {
      steps {
        echo 'building...'
      }
    }
  }
}
