pipeline {
    agent any
    options{
        timeout(time: 5000, unit: 'SECONDS')
        retry(2)
        checkoutToSubdirectory('test')
        timestamps()
    }
    stages{
        stage('My first stage') {
            steps{
                sh 'sdfdsfsdf'
            }
        }
    }
}
