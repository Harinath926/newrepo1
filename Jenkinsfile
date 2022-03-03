pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
           echo "build"     
                sh "javac Add.java"
            }
        }
        stage('execute') { 
            steps {
               echo "test"
                sh "java Add"
            }
        }
        stage('Deploy') { 
            steps {
              echo "deploy" 
            }
        }
    }
}
