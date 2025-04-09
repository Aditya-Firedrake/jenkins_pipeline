pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                 git branch: 'main', 
                url: 'https://github.com/DevMadhup/Springboot-BankApp.git'
            }
        }
        stage('Build') {
            steps {
                // Example for Maven project
                sh 'mvn clean package'
                
                // For Node.js project, you might use:
                // sh 'npm install'
                // sh 'npm run build'
            }
        }
    }
}
