pipeline{
    agent any
 
    stages {

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
