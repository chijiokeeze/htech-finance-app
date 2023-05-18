pipeline {
    agent {
        docker {
            image 'maven'
        }
    }
    stages {
        stage('Build'){
            steps {
                sh 'echo this is my 1st Project'
                }
            }
        stage('sonarqube'){
            steps {
                sh 'mvn --version'
                }
            }
        stage('docker stage'){
            steps {
                sh 'echo this is my 3rd Project'
            }
        }    
    }
    post{
        always {
            cleanWs()
        }
    }    
}
