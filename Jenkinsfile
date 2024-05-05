pipeline{
    agent any
    environment{
        USERNAME=credentials('upendra_creds_USR')
        //PASSWORD=credentials('upendra_creds_PSW')
    }
    stages{
        stage('My first stage'){
            steps{
                sh 'echo "username is $USERNAME" '
                //sh 'echo "password is $PASSWORD" '

            }
        }
    }
}
