pipeline{
    agent any
    stages {
        stage('install Dependencies'){
            steps{
                echo '********Installing dependencies*************'
                // sh npm install
            }
        }

        stage('test'){
            steps{
                echo '********Testing Application******************'
                // cd ./calc-server
                // sh npm run test
            }
        }

        stage('build'){
            steps{
                echo '********Building Application******************'
            }
        }
    }
}