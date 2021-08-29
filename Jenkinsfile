pipeline {
  agent any;
  tools {
    nodejs 'jenkins-nodejs'
  }
  stages {
    
    stage('Initialize') {
      steps {
           npm install
            } 
    }
    
    stage('Unit tests') {
      steps {
            npm test -- --coverage --watchAll=false
            }
    }
    
    stage('Build') {
      steps {
           npm run build
            }
    }
  }
}
    
    
      
    
