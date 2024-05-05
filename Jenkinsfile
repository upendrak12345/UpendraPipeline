pipeline{
    agent any
    environment{
        USERNAME=credentials('upendra_creds')
        //PASSWORD=credentials('upendra_creds_PSW')
    }
    stages{
        stage('My first stage'){
            steps{
                sh 'echo  $USERNAME '
                //sh 'echo "password is $PASSWORD" '

            }
        }
    }
}
