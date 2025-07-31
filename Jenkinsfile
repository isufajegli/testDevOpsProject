pipeline {
    agent any
    stages {
        stage('Build Docker Image') {
            steps {
                script {
                    echo 'Building the Docker image...'
                    docker.build('your-dockerhub-username/abc-tech:latest', '.')
                }
            }
        }
    }
}
