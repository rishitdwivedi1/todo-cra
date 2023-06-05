pipeline {
    agent any
    tools { nodejs "Nodejs v20.2.0" }
     environment {
            CI = 'true'
        }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
                sh 'npm start'
            }
        }
      
               
           

    }
}
