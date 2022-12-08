pipeline{
    agent any 
    stages{
        stage('1-clone the repo'){
            steps{
                sh 'ps -ef'
            }
        }
        stage('2-systemcheck'){
            steps{
                sh 'df -h'
            }
        }
        stage('3-system memory'){
            steps{
                sh 'sudo free -m'
            }
        }
        stage('4-check cpu information'){
            steps{
                sh 'lscpu'
            }
        }
    }
}