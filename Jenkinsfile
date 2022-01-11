pipeline {
    agent {
        node {
            label 'custom'
        }
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
