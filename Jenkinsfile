pipeline {
    agent any 
    stages {
        stage('cloning') { 
            steps {
                git credentialsId: 'd24f6d92-98fe-4c8e-a98f-6b81cfd0854c', url: 'https://github.com/ShivamAsthana/Project.git'
            }
        }
        stage('deploying') { 
            steps {
                sh 'ls'
                sh 'pwd'
                sh 'scp -r /var/lib/jenkins/workspace root@65.2.35.96:/root/home'
                
                
            }
        }        
    }
}
