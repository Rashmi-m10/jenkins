pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                javac Hello.java
            }
        }
        stage('Run') {
            steps {
                java Hello
            }
        }
    }
}
