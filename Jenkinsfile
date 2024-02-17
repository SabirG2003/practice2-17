pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    // Run 'hello-world' Docker container
                    docker.image('hello-world').run()
                }
            }
        }
    }
}
