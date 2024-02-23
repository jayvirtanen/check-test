// Uses Declarative syntax to run commands inside a container.
pipeline {
    agent {
        kubernetes {
            inheritFrom 'ubuntu'
            defaultContainer 'ubuntu'
        }
    }
    stages {
        stage('Main') {
            steps {
                sh 'hostname'
            }
        }
    }
}
