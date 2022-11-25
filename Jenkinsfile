pipeline {
    agent Kubernetes
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