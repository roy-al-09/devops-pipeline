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
                job: 'build'
            }
        }

        stage('Deploy Job') {
            steps {
                job: 'deployed'

            }
        }
    }
}
