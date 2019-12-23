pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                sh 'mocha -V'
            }
        }
    }
}
