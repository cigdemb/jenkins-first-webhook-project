pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'POLL Update for the second time'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}










