pipeline{
    agent any
    triggers{
        pullSCM('* * * * *')
    }
    stages{
        stage('Unit test'){
            steps{
                sh 'python test_calculator.py'
            }
        }
    }
}