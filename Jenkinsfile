pipeline {
    agent any
    stages {
        stage("checkout") {
            steps {
                checkout scm
            }
        }
        stage("Test") {
            steps {
                bat 'sudo npm install'
            }
        }
        stage('build') {
            steps {
                bat 'npm run build'
            }
        }
    
    }
}
