pipeline {
    agent {label 'Prokas'}

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sleep time: 60, unit: 'SECONDS'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}