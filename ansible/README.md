pipeline(){
    agent any
    stages(){
        stage('build'){
            steps{
                sh "du -h"
            }
        }
        stage('test'){
            steps{
                sh "cat /etc/os-release"
            }
        }
        stage('deploy'){
            steps{
                sh "mpstat"
            }
            
        }
    }
}
