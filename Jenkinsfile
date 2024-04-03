pipeline{
    agent any

    stages{
        stage('build'){
            steps{
              sh  'sudo apt install nodejs'
             sh 'npm install'
            }
        }
         stage('Test'){
            steps{ 
            sh 'node app.test.js'  
            }
        }
        stage('Deploy/Deliver'){
            steps{
                 echo 'Deploying'
            }
        }
    }
}