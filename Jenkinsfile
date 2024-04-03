pipeline{
    agent any

    stages{
        stage('build'){
            steps{
             sh 'npm install'
            }
        }
         stage('Test'){
            steps{
                run{
                sh 'node app.test.js'
                }
            }
        }
        stage('Deploy/Deliver'){
            steps{
                 echo 'Deploying'
            }
        }
    }
}