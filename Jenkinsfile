pipeline {
    agent any

    stages {
        stage('Setup') {
            steps {
                
                sh 'sudo apt update'
                sh 'sudo apt install -y nodejs'
            }
        }
        stage('Build') {
            steps {
                
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
              
                sh 'npm test'
            }
        }
        stage('Deploy/Deliver') {
            steps {
               
                echo 'Deploying'
              
            }
        }
    }
}
