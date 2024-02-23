// Uses Declarative syntax to run commands inside a container.
pipeline {
    agent {
        kubernetes {
            inheritFrom 'ubuntu'
            defaultContainer 'ubuntu'
        }
    }
    stages {
        stage('First Stage') {
            steps {
                sh 'hostname'
            }
        }
        stage('Second Stage'){
            steps{
                sh 'hostname'
            }
        }
        stage('Third Stage'){
            steps{
                sh 'hostname'
            }
        }
    }
}
