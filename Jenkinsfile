pipeline{
    
    agent any

    stages{
        stage('build'){
            steps{
                bat 'npm install'
            }
        }
        stage('test'){
            steps{
                bat 'echo "testing the application"'
            }
        }
        stage('deploy'){
           steps{
                bat 'echo "deploying the application"'
            } 
        }
    }

}