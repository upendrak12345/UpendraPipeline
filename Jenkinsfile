pipeline {
    agent any
    options{
        timeout: 2, unit: 'SECONDS'
        retry(2)
        checkoutToSubdirectory('test')
    }
    stages{
        stage('My first stage') {
            steps{
                sh 'sdfdsfsdf'
            }
        }
    }
}
