pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building"
                sh 'echo "${env.BRANCH_NAME}"'
            }
        }
        stage('Test') {
            steps {
                echo "Testing..."
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploy..."
            }
        }
    }
}
