pipeline {
       agent any
       stages{
              stage('Build') {
                   steps {
                            sh 'mvn -B -U surefire:test -DtestFailureIgnore=true'
                   }
              }
              stage('Test') {
                steps{
                        sh 'mvn test'
                }
              }
       }
}
