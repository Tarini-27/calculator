pipeline{
  agent any;
  tools {
    nodejs 'jenkins-nodejs'
  }
  stages {
    
    stage('Initialize') {
      steps {
        sh ***
          npm install
        ***
      }
    }
    
    stage('Unit tests') {
      steps {
        sh ***
          npm run test -- --watchAll=false
        ***
      }
    }
    
    stage('Build') {
      steps {
        sh ***
          npm run build
        ***
      }
    }
    
    
      
    
