pipeline{
    agent any
    environment{
        env_node='PRODUCTION'
    }
    stages{
        stage('My First Stage'){
            steps{
                sh 'echo $env_node'
            }
        }
    }
}
