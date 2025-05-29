pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building Java application...'
                sh 'javac SimpleJavaProgram.java'
            }
        }
        stage('Run') {
            steps {
                echo 'Running Java application...'
                sh 'java SimpleJavaProgram'
            }
        }
    }
}