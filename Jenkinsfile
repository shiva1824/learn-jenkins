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
                sh echo 'echo This is Test'
            }
        }
        stage('Deploy') { 
            steps {
                sh echo 'echo This is Deploy'
            }
        }
    }

    post {
        always{
            echo "This sections runs always"
            deleteDir()
        }
        success{
            echo "This section run when pipeline success"
        }
        failure{
            echo "This section run when pipeline failure"
        }
    }
}