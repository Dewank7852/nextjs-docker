pipeline {
    agent {
        docker {
            image 'dewankchauhan7852/next:latest' 
            args '-p 3000:3000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
