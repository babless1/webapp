pipeline {
    agent any

    stages {
        stage('Cloning Repo') {
            steps {
                echo 'Cloning Github Repo'
            }
        }
        stage('Build App') {
            steps {
                echo 'Build the App'
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
