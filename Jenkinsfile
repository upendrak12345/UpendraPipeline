pipeline{
    agent any
    parameters{
        choice(name:'pick' , choices:['One', 'Two', 'Three'], description: ' Pick something')
    }
    stages{
        stage('My First Stage'){
            steps{echo "Choice: ${params.pick}"}
            
        }
    }
}
