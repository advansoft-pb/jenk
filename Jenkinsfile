/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'maven:3.9.11-eclipse-temurin-17-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'cd $HOME'
                sh 'pwd'
                sh 'ls -al'
            }
        }
    }
}

