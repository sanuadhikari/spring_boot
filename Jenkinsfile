 pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'mvn clean verify'
            }
        }
        stage('Publish') {
            steps {
                echo 'Publishing'
            }
        }
    }