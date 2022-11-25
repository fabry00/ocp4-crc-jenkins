pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                container('nodejs') {
                    sh 'npm install' 
                }
            }
        }
    }
}