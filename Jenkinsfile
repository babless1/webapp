pipeline {
    agent any

    stages {
        stage('Cloning Repo') {
            steps {
                git credentialsId: 'a5b3dfb8-7286-4f55-a68b-1d849a1c46e9', url: 'https://github.com/babless1/webapp.git'
            }
        }
        stage('Build App') {
            steps {
                sh 'mvn clean package'
            }
        }
        stage('Code Review') {
            steps {
                echo 'Code Analysis'
            }
        }
        stage('Upload artifacts') {
            steps {
                echo 'Uploading the package into Nexus'
            }
        }
        stage('Deploy App') {
            steps {
                echo 'Deploying the app into environment'
            }
        }
        
    }
}
