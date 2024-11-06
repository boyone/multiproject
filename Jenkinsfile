pipeline {
       agent any

       stages {
           stage('Hello 1') {
               steps {
                   sh 'cat first/README.md'
               }
           }
           stage('Hello 2') {
               steps {
                   sh 'cat second/README.md'
               }
           }
       }
   }