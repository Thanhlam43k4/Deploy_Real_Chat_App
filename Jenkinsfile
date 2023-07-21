pipeline{
    agent any
    stages {
        stage('Build'){
            steps{
                echo "Branch is ${env.BRANCH_NAME}..."

                withNPM(npmrcConfig:'my-custom-npmrc') {
                echo "Performing npm build..."
                sh 'npm install'
                }
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
