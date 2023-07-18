pipeline{
    agent any
    stages{
        stage('Build'){
            step{
                sh 'npm install'
            }
        }
        stage('Test'){
            step{
                sh './jenkins/scripts/test.sh'
            }
        }
    }
}