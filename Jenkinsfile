pipeline {
    agent any

    environment {
        CI = 'true'
    }
    stages {
        stage('Build') {
            steps {
                echo 'building the software'
                sh 'npm install'
            }
        }
    }
}