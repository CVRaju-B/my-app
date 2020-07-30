pipeline { 
  agent any 
  
  stages {
    stage ('Install dependencies') {
      steps {
        sh "echo $PATH"
        sh "npx install"
      }
    }
    stage ('Build') {
      steps {
        echo 'building...'
      }
    }
  }
}
