pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/DonthineniSanthosh/CDD.git'

            }
        }
        stage('Build') {
            steps {
                echo "Building the application..."
                // Add your build command (e.g., mvn package, npm install)
            }
        }
        stage('Test') {
            steps {
                echo "Running tests..."
                // Add test commands (e.g., mvn test, npm test)
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying the application..."
                // Add deployment commands if needed
            }
        }
    }
}
