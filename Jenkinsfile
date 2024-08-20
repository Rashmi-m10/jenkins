
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
               git branch:'master' url: 'https://github.com/Rashmi-m10/jenkins.git'
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
