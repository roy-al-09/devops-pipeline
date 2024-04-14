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
                'build'
            }
        }

        stage('Deploy Job') {
            steps {
                'deployed'

            }
        }
    }
}
