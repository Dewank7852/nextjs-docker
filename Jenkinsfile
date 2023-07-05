pipeline {
  agent any
  
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
        sh 'npm run build'
      }
    }
    
    stage('Test') {
      steps {
        sh 'npm run start -- -p 8081'
      }
    }
    
    stage('Deploy') {
      steps {
        sh 'npm run deploy'  // Customize this command based on your deployment setup
      }
    }
  }
}
