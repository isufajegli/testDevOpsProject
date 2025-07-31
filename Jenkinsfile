pipeline {
    agent any
    stages {
        stage('Build Image in Minikube') {
            steps {
                echo 'Building the Docker image for Minikube...'
                sh '''
                    eval $(minikube -p minikube docker-env)
                    docker build -t abc-tech:latest .
                '''
            }
        }
    }
}
