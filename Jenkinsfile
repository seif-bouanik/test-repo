pipeline {
    agent any
    stages {
        stage('Build Stage') {
            steps{
                sh 'python ./New_Commit.py'
            }
        }
        stage('Deploy Stage') {
            steps{
                echo 'Deploy Application Here'
            }  
        }
    }
}
