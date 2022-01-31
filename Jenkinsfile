pipeline {
    agent any
    stages {
        stage('yamllint') {
            steps {
                sh "find . -regex \".*\\.ya*ml\""
            }
        }
    }
}