pipeline {
    agent any

    stages {
        stage('check') {
            steps {
                sh '''
                    docker version
                    docker info
                    docker compose version
                    curl --version
                    jq --version
                '''
            }
        }
    }
}
