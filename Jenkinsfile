pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
        stage('test') {
            steps {
                sh 'python test.py'
            }
        }
        stage('package') {
            steps {
                sh 'echo "Running Package stage"'
            }
        }
        stage('deploy') {
            steps {
                sh 'echo "Running Deploy stage"'
            }
        }
    }
}
