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
                build job: 'build'
            }
        }

        stage('Deploy Job') {
            steps {
                build job: 'deployed'

            }
        }
    }
}
