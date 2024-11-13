pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    bat 'javac HelloWorld.java'
                    bat 'java HelloWorld'
                }
            }
        }
        stage('Merci') {
            steps {
                script {
                    bat 'javac Merci.java'
                    bat 'java Merci'
                }
            }
        }
        stage('DeRien') {
            steps {
                script {
                    bat 'javac DeRien.java'
                    bat 'java DeRien'
                }
            }
        }
    }
}
