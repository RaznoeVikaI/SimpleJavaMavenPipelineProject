pipeline {
       agent any
       stages{
              stage('Build') {
                   sh 'mvn -B -U clean package -Dmaven.test.skip=true'
              }
              stage('Test') {
                   sh 'mvn test'
              }
       }
}
