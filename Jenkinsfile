pipeline{
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
          npm run test -- --watchAll=false
          return null
      }
    }
    
    stage('Build') {
      steps {
          npm run build
      }
    }
  }
}
    
    
      
    
