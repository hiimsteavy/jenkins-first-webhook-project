pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compiling the Java source code'
                sh 'javac Hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running the compiled Java code v3.'
                sh 'java Hello'
            }
        }
    }
}