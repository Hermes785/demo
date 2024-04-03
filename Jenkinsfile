pipeline{
    agent any
    tools{
        nodejs 'nodejs'
    }
  
    stages{
        stage('build'){
            steps{
             echo('building')
             sh 'npm install'
            }
        }
         stage('Test'){
            echo ('test)
            steps{ 
            sh 'npm testing'  
            }
        }
        stage('Deploy/Deliver'){
            steps{
                 echo 'Deploying'
            }
        }
    }
}