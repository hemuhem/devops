pipeline(){
    agent any 
    stages(){
        stage('first stage'){
            steps{
                sh "ifconfig"
            }
            
        }
        stage('second stage'){
            steps{
                sh "cat /etc/os-release"
            }
            
        }
    }
    
}
