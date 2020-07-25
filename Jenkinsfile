pipeline {
   agent any

   stages {
      stage('Checkout') {
         steps {
            git 'https://github.com/vivra-git/hello-world-java.git'
         }
      }
      stage('Build'){
        steps {
            sh 'javac HelloWorld.java'
        }
      }
   }
}
