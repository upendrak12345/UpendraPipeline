pipeline{
    agent any
    environment{
        USER=credentials('upendra_ssh')
    }
    stages{
        stage('My First Stage'){
            steps{
                sh 'echo $USER_USR'
                sh 'echo $USER'
            }
        }
    }
}
