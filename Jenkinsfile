pipeline {
    agent any
    parameters{
        choice(name: 'Choose', choices:['one','two','three'],description:'')
    }
    stages{
        stage('My First Stage'){
            steps{
                sh ' echo $params.Choose'
            }
        }
    }
}
