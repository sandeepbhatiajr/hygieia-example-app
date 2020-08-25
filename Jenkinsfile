pipeline {
    agent any
    tools {
        jdk 'jdk11'
    }
    stages {
        stage('Build') {
            steps {
                sh './gradlew build'
            }
        }
    }
}