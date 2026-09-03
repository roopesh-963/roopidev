pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                bat 'javac main.java'
            }
        }
        stage('Run'){
            steps{
                bat 'java main'
            }
        }
    }
}
