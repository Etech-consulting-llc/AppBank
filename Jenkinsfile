pipeline{
    agent any 
        stages{
            stage('1-clone'){
                steps{
                  
                sh 'df -h'
                }
            }
            stage('2-memory-check'){
                steps{
                  
                sh 'lscpu'
                }
            }
            stage('3-welcome-page'){
                steps{
                  
                sh 'git --version'
                }
            }
    }
}