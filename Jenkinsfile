pipeline{
    agent any

    tools {
        nodejs 'nodejs-18'
    }
 
    stages {
        stage('CheckOut Code') {
            steps{
                git 'https://github.com/bhanuprakash515/jobby-app-react-suing-jenkins.git'
            }
        }

        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }

        stage('Node Version') {
            steps {
                sh 'npm -v'
            }
        }  
        
    }
}
