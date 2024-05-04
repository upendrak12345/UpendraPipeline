pipeline{
    agent{
        docker {
            image: pbweb/yarn-prometheus-exporter
            args '-v /tmp:/tmp'
        }
    }
    stages{
        stage('Example Stage'){
            steps{
                sh 'cat /etc/os-release'
                sh 'df -Ph'
            }
        }
    }
}
