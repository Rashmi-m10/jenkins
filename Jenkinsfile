
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
               git url: ''
            }
        }
        stage('Build') {
            steps {
               sh 'javac Hello.java'
            }
        }
        stage('Run') {
            steps {
               sh 'java Hello'
            }
        }
    }
}
