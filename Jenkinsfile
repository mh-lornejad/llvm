pipeline {
    agent any 
    stages {
        stage('Clone the repo') { 
            steps {
                echo "Clone the repo"
                sh "rm -fr llvm"
                sh "git clone https://github.com/mh-lornejad/llvm.git"
            }
        }
        stage('Test') { 
            steps {
                echo "Test"
            }
        }
        stage('Deploy') { 
            steps {
                echo "Deploy"
            }
        }
    }
}
