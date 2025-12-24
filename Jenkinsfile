pipeline{
    agent any
 
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
