pipeline{
    agent any

    stages{
        stage('My first stage'){
            environment{
                USERNAME=credentials('upendra_creds')
            }
            steps{
                sh 'printenv '

            }
        }
        stage('My Second stage'){
            steps{
                sh 'printenv'
            }
        }
    }
}
