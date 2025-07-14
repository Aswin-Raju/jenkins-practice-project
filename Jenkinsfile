pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }
        stage('Test') {
            steps {
                sh 'python3 hello-world/test_app.py'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy step (mock)'
            }
        }
    }
}
