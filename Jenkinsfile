pipeline {
  agent any
  
  stages {
    stage('Install dependencies') {
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
        sh 'npm run start -- -p 8082'
      }
    }
  }
}
