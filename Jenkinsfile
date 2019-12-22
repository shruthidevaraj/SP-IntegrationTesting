pipeline {
  agent any
    
    
  stages {
                
    stage('Install dependencies') {
      steps {
        sh 'scripts/script.sh'
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
