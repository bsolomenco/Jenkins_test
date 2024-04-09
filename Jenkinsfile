pipeline {
    agent {label 'Prokas'}

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sleep time: 30, unit: 'SECONDS'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sleep time: 20, unit: 'SECONDS'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                sleep time: 10, unit: 'SECONDS'
            }
        }
    }
}