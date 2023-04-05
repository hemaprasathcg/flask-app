pipeline {
    agent { base }
    stages {
        stage('build') {
            steps {
                sh 'pip install flask'
            }
        }
        stage('test') {
            steps {
                sh 'python app.py'
            }
        }
    }
}