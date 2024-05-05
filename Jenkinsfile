pipeline{
    agent {
        docker {image 'amazonlinux'}
    }
    stages{
        stage('First Stage'){
            steps{
                echo "Hello World"
            }
        }
        stage('Second Stage'){
            steps{
                sh 'uname -a'
            }
        }
    }
    post{
        awlays{
            echo "Hello World"
        }
    }

}
