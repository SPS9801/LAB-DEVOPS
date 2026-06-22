pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                // Clones the Git repository using the built-in Git step
                git branch: 'main', 
                    credentialsId: '', 
                    url: 'https://github.com/SPS9801/LAB-DEVOPS.git'
            }
        }
        stage('Build & Test') {
            steps {
                echo 'Running steps on the manually fetched repository...'
                sh 'ls -la' 
            }
        }
    }
}
