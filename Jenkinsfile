pipeline {
    agent any
    stages {
        stage('Build') { 
            container('nodejs') {
                steps {
                    sh 'npm install' 
                }
            }
        }
    }
}