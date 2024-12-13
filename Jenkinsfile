pipeline {
    agent {
        label Agent-1
    } 

    stages {
        stage('Build') { 
            steps {
                sh 'echo This is bulid'
            }
        }
        stage('Test') { 
            steps {
                sh 'echo This is Test'
            }
        }
        stage('Deploy') { 
            steps {
                sh 'echo This is Deploy'
            }
        }
    }
}