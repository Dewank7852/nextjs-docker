pipeline {
  agent any
  
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
        }
    }
    
   stage('Build') {
      steps {
        sh 'npm run build'
      }
    } 
    stage('Deploy') {
      steps {
        sh 'npm run deploy'
      }
    }
  }
}
