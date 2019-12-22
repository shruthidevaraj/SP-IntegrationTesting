pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                echo "I AM HERE, EXECUTING THIS LINE"
                mocha MyBooking/MyBooking.js
            }
        }

        stage ('Testing Stage') {

            steps {
                withMaven(maven : 'maven_3_5_0') {
                    sh 'mvn test'
                }
            }
        }


        stage ('Deployment Stage') {
            steps {
                withMaven(maven : 'maven_3_5_0') {
                    sh 'mvn deploy'
                }
            }
        }
    }
}
