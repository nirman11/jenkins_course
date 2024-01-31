pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                sh 'git clean -qffxd'
                sh 'python -m pytest'
            }
        }
    }
}
