pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'POLL Update'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}










