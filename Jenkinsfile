pipeline {
    agent any
    stages {
        stage('CLEAN PREVIOUS') {
            steps {
                sh "mvn clean"
            }
        }
        stage('TEST') {
            steps {
                sh "mvn test"
            }
        }
        stage('PACKAGE DEPLOY') {
            steps {
                sh "mvn package"
            }
        }
    }
}
