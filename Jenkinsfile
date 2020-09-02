pipeline {
         agent any
         stages {
                 stage('Build') {
                 steps {
                     echo 'Hi, this is AYUSH '
                 }
                 }
                 stage('Test') {
                 steps {
                    input('Do you want to proceed?')
                 }
                 }
                 stage('Deploy') {
                 when {
                       not {
                            branch "master"
                       }
                 }
                 steps {
                       echo "Hello"
                 }
                 }
                
                           
                           
              }
}
