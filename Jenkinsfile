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
                sleep time: 40, unit: 'SECONDS'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                sleep time: 30, unit: 'SECONDS'
            }
        }
    }
}