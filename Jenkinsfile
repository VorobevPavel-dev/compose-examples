pipeline {
    agent {
        node {
            label 'centos'
        }
    }
    stages {
        stage('yamllint') {
            agent {
                docker{
                    image 'cytopia/yamllint:latest'
                    reuseNode true
                }
            }
            steps {
                sh "find . -regex \".*\\.ya*ml\" -exec yamllint -c ./.yamllint {} \\;"
            }
        }
    }
}