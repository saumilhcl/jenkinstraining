pipeline {
    agent any

    stages {
        stage('Git') {
            steps {
               git 'https://github.com/saumilhcl/jenkinstraining.git'
            }
        }
        stage('Build')
        {
            steps{
                bat 'npm install'
            }
        }
         stage('Email')
        {
            steps{
                echo 'email sent'
            }
        }
        
    }
}
