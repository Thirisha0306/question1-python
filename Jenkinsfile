pipeline{
    agent any
    stages{
        stage('checkout code'){
            steps{
                git 'https://github.com/Thirisha0306/question1-python.git'
            }
        }
        stage('Build'){
            steps{
                bat 'python main.py 10 20'
            }
        }
    }
}