pipeline {
    agent {
        kubernetes {
            yamlFile 'pod.yaml'
        }

    }
    stages {
        stage('Build') {
            steps {
                container('node') {
                    sh 'ls -la'
                    sh 'node --version'
                 }
            }
        }
    }
}
