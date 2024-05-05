pipeline{
    agent any
    environment{
        USERNAME=credentials('upendra_creds')
        //PASSWORD=credentials('upendra_creds_PSW')
    }
    stages{
        stage('My first stage'){
            steps{
                sh 'echo  $USERNAME_USR '
                //sh 'echo "password is $PASSWORD" '

            }
        }
    }
}
