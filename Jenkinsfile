pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
           echo "Hello world"     
                sh "hello.py"
            }
        }
        stage('execute') { 
            steps {
               echo "test"
                sh "python Hello"
            }
        }
        stage('Deploy') { 
            steps {
              echo "deploy" 
            }
        }
    }
}
