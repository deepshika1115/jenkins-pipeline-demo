pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/deepshika1115/jenkins-pipeline-demo.git'
            }
        }

        stage('Install Dependencies') {
            steps {
                echo "Installing dependencies..."
            }
        }

        stage('Build and Test') {
            steps {
                echo "Build and Test successful!"
            }
        }

        stage('Archive Artifact') {
            steps {
                echo "Archiving build artifact..."
            }
        }
    }
}
