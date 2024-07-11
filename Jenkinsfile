pipeline {
    agent any
    
    tools{
        maven 'maven3'
    }
    stages {
        stage('Maven Build') {
            steps {
                sh 'mvn compile'
            }
        }
        stage('Maven Test') {
            steps {
                sh 'mvn test'
            }
        }
        stage('Maven Package') {
            steps {
                sh 'mvn package' 
            }
        }
    }
}
