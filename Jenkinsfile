pipeline {
    agent any
    stages{
        stage("First Stage"){
            input{
                message 'Enter the details'
                ok ' Ok to proceed'
                submitter 'admin'
                parameters{
                    choice(name: 'choose', choices:['one','two','three'],description:'Choose one')
                }
            }
            steps{
                echo "${choose}"
            }
        }
    }

}
