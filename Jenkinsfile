pipeline {
    agent any
            
    stages {
        stage('Build') {
            steps {
                echo "Building.."
                sh 'python3 hello.py'
                
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver....'
               
            }
        }
    }
}