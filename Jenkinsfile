pipeline {
    agent any
    environment {
        PATH = "C:\\Users\\rabia\\AppData\\Roaming\\npm;${env.PATH}"
    }
    stages {
        stage('Install Dependencies') {
            steps {
                // Change directory and run npm install
                dir('Simple-typescript-project-jenkin') {
                    bat 'npm install'
                }
            }
        }
        stage('Build') {
            steps {
                // Change directory and run the build command
                dir('Simple-typescript-project-jenkin') {
                    bat 'npm run build'
                }
            }
        }
               
    }
}
