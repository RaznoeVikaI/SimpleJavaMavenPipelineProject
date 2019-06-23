pipeline {
    agent any
    tools {
        maven 'myMaven'
    }
    stages {
        stage('Maven version') {
            steps {
                sh 'mvn --version'
            }
        }
        stage('---clean---') {
            steps {
                sh "mvn clean"
            }
        }
         stage('--test--') {
            steps {
                sh "mvn test"
            }
        }
        stage('--package--') {
            steps {
                sh "mvn package"
            }
        }
    }
}