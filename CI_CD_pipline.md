# jinkins-_-demo1


pipeline {
    agent any
    
    pipeline {
    agent any
    
    
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Add your test commands here, e.g., mvn test
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
               
            }
        }
    }

    
