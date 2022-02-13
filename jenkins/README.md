<<<<<<< HEAD
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
=======
hello "govindu"
>>>>>>> c3ba0107cb5974c6e44fefd88061aecb28b34090
