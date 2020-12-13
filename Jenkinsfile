pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                withMaven(maven : 'apache-maven-3.6.1'
                sh 'mvn clean compile'
            }
        }
    }
}