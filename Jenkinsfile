pipeline {
    agent any

    stages {
        stage('Build') {
            steps{
                sh 'javac src/Main.java'
            }
        }
        stage('Run'){
            steps{
                sh 'java src/Main'
            }
        }
    }
}