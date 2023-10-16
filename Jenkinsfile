pipeline {
    agent any

    stages {
        stage('Build') {
            steps{
                sh 'javac -d . src/Main.java'
            }
        }
    }
}