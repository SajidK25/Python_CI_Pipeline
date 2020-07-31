pipeline{
    agent any
    trigger{
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