pipeline{
    agent{
        docker {image 'amazonlinux'}
    }
    stages{
        stage('First Stage') {
            steps{
                sh 'df -Ph'
                echo 'cat /etc/os-release'
            }
        }
    }
    post{
        success{
            echo "Pipeline has been run successfully"
        }
        failure{
            echo "Pipeline has failed to run"
        }
        always{
            echo "Jenkins pipeline has been completed"
        }
        cleanup{
            echo "Testing cleanup condition"
        }
    }
}
