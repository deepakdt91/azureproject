pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'git@github.com:deepakdt91/azureproject.git'
            }
        }
        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }
        stage('Build') {
            steps {
                echo 'No build step required for this simple app.'
            }
        }
        stage('Deploy to Azure') {
            steps {
                // Example assumes you're using SCP to transfer, or use Azure CLI
                sh 'echo Deploy step placeholder - replace with Azure CLI or FTP script'
            }
        }
    }
}
