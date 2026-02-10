pipeline {
    agent any
    stages {
        stage("Build") {
            steps {
                echo "Building the project..."
                sh "./build.sh"
            }
        }
        stage("Deploy") {
            steps {
                echo "Deploying the project..."
                sh "./deploy.sh"
            }
        }
    }
}

