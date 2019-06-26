pipeline {
       agent any
       stages{
              stage('Build') {
                   steps {
                            sh 'mvn -B -U clean package -Dmaven.test.skip=true'sh 'echo Hello'
                   }
              }
              stage('Test') {
                steps{
                        sh 'mvn test'
                }
              }
       }
}
