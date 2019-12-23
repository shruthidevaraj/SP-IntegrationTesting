pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                mocha -V
            }
        }
    }
}
