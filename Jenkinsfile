pipeline {
    agent {
        label 'custom'
    }
    stages {
        stage('Build') {
            steps {
                    sh 'ls -la'
                    sh 'skaffold'
            }
        }
    }
}
