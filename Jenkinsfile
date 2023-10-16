pipeline {
    agent any

    stages {
        stage('Build') {
            steps{
                sh 'javac -d . src/Main.java'
            }
        }
        stage('Run'){
            steps{
                sh 'java -cp . src.Main'
            }
        }
    }
}