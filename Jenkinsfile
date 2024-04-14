pipeline {
    agent any

    stages {
        stage('First Job to Print') {
            steps {
                sh 'echo hello_jenkins'
            }
        }

        stage('Build Job') {
            steps {
                sh 'echo build'
            }
        }

        stage('Deploy Job') {
            steps {
                sh 'echo deployed'

            }
        }
    }
}
