Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'python:3.9' } }
    stages {
        stage('build') {
            steps {
                sh 'python3 --version'
            }
        }
    }
}