pipeline{
    agent {
        docker {
            image 'node:16-alpine'
            args '-v /tmp:/tmp'
        }
    }
    stages{
        stage('Example Stage'){
            steps{
                sh 'node --version'
                sh 'df -Ph'
            }
        }
    }
}
