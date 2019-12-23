pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                sh 'mocha MyBooking/Mybooking.js'
            }
        }
    }
}
