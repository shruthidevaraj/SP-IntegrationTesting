pipeline {
  agent any
    
  tools {nodejs "node"}
    
  stages {
    stage('Test') {
      steps {
        echo "I AM HERE, EXECUTING THIS LINE"
        mocha MyBooking/MyBooking.js
      }
    }      
  }
}
