pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Naveen4421/simple'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                // You can add build commands here like `sh 'make'` or `sh './gradlew build'`
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add test commands like `sh 'make test'`
            }
        }
    }
}
