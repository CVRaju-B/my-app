pipeline { 
  agent any 
  
  tools {
    nodejs 'node'
  }
  
  stages {
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
