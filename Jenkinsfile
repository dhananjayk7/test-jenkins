pipeline {
    agent { docker { image 'python:3.7.2' } }
    stages {
        stage('build') {
            steps {
                sh 'python3 --version'
                sh 'python3 helloworld.py'

            }
        }
    }
}