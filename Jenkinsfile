pipeline {
  agent any
    
  tools {nodejs 'nodejs 18.4.0'}
    
  stages {

    stage('Build') {
      steps {
        echo 'building the software'
        sh 'npm version'
      }
    }  
    
  }
}