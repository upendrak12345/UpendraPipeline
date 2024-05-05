pipeline{
    agent any

    stages{
        stage('My first stage'){
            environment{
                USERNAME=credentials('upendra_creds')
            }
            steps{
                sh 'echo username is $USERNAME '

            }
        }
        stage('My Second stage'){
            steps{
                sh 'echo username is $USERNAME '
            }
        }
    }
}
