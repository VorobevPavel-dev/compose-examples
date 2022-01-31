pipeline {
    agent {
        docker { image 'cytopia/yamllint'}
    }
    stages {
        stage('yamllint') {
            steps {
                sh "find . -regex \".*\\.ya*ml\" -exec yamllint -c ./.yamllint {} \\;"
            }
        }
    }
}