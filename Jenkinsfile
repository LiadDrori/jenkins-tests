pipeline {
    kubernetes {
      yamlFile 'pod.yaml'
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
