pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                nodejs('node-16.14.0') {
                    sh 'npm ci'
                }
            }
        }
    }
}
