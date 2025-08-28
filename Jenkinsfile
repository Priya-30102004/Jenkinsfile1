pipeline {
    agent any

   
    stages {
        stage('Build') {
            steps {
                echo "Hello Build stage"
                sh 'pwd'
            }
        }
         stage('test') {
             steps {
                 echo "Hi test stage"
                 sh 'ls'
            }
         }
         stage('Deploy') {
             steps {
                 echo "Welcome Deploy stage"
                 sh 'date'
             }
         }
     }
}
              
