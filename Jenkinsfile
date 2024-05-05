pipeline {
    agent any
    options{
        timeout(time: 5000, unit: 'SECONDS')
        retry(2)
        checkoutToSubdirectory('test')
        timestamps()
        skipDefaultCheckout()
    }
    stages{
        stage('My first stage') {
            steps{
                sh 'sdfdsfsdf'
            }
        }
    }
}
