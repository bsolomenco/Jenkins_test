pipeline {
    agent none

    stages {
        stage('Build') {
            agent {label 'Prokas'}
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            agent {label 'Prokas'}
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            agent {label 'Prokas'}
            steps {
                echo 'Deploying....'
            }
        }
    }
}