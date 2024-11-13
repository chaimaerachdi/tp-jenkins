pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    sh 'javac HelloWorld.java'
                    sh 'java HelloWorld'
                }
            }
        }
        stage('Merci') {
            steps {
                script {
                    sh 'javac Merci.java'
                    sh 'java Merci'
                }
            }
        }
        stage('DeRien') {
            steps {
                script {
                    sh 'javac DeRien.java'
                    sh 'java DeRien'
                }
            }
        }
    }
}
