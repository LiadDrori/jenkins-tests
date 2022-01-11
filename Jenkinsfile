pipeline {
    agent {
        kubernetes {
        yamlFile 'pod.yaml'
        }

    }
    stages {
        stage('Build') {
            steps {
                container('dude-on-shipod') {
                    sh 'ls -la'
                    sh 'node --version'
                 }
            }
        }
    }
}
