pipeline{
    agent any
    tools{
        nodejs 
    }

    stages{
        stage('build'){
            steps{
              
             sh 'npm install'
            }
        }
         stage('Test'){
            steps{ 
            sh 'npm test'  
            }
        }
        stage('Deploy/Deliver'){
            steps{
                 echo 'Deploying'
            }
        }
    }
}