pipeline{
    agent {
        docker{
            image 'amazonlinux'
            args '-v /tmp:/tmp'
        }
    }
    stages {
        stage('My First stage'){
            steps{
                sh 'df -Ph'
                sh 'cat /etc/os-release'
            }
        }
    }
}
