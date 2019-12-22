pipeline {
  agent any
    
#  tools {nodejs "node"}
    
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
