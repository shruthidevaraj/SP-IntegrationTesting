pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                mocha MyBooking/Mybooking.js
            }
        }
    }
}
