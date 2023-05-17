pipeline {
    agent none
    stages {
        stage('Build'){
            agent any
            steps {
                sh 'echo this is my 1st Project'
                }
            }
        stage('sonarqube'){
            agent any
            steps {
                sh 'echo this is my 2nd Project'
                }
            }
        stage('docker stage'){
            agent any
            steps {
                sh 'echo this is my 3rd Project'
            }
        }    
    }
}
