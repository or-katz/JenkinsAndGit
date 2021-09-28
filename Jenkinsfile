pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('checkout') {
            steps {
                checkout scm
            }
        }
        stage('list files') {
            steps {
                sh 'ls'
            }
        }
        stage('run python script') {
            steps {
                python3 main.py
            }
        }
    }
}