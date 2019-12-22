pipeline {
  agent any
    
  tools {nodejs "node"}
    
  stages {
                
    stage('Install dependencies') {
      steps {
        sh 'npm install'
      }
    }
     
    stage('Test') {
      steps {
        echo "I AM HERE, EXECUTING THIS LINE"
        mocha MyBooking/MyBooking.js
      }
    }      
  }
}
