pipeline{
    agent any
    stages {
        stage('Build'){
            steps{
                
                bat 'npm install'
            }
        }
        stage('Test'){
            steps{
                sh './jenkins/scripts/test.sh'
            }
        }
        stage('Deploy'){
            steps{
                echo 'Deploying .....'
            }
     }
}
}
