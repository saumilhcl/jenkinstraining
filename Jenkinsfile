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
        stage('Test')
        {
            steps{
                echo 'test cases script to be added here'
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
