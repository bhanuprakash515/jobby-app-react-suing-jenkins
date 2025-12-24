pipeline{
    agent any
    tools{
        nodejs 'node18'
    }
 
    stages {
        stage('CheckOut Code') {
            steps{
                git 'https://github.com/bhanuprakash515/jobby-app-react-suing-jenkins.git'
            }
        }

        stage('install Dependencies'){
            steps{
                sh 'npm install'
            }
        }
        stage("Chack Version"){
            steps{
                sh 'node -v'
            }
        }

        
    }
}
