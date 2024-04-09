Jenkinsfile (Declarative Pipeline)
pipeline {
    agent none

    stages {
        stage('Build') {
            agent 'Prokas'
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            agent 'Prokas'
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            agent 'Prokas'
            steps {
                echo 'Deploying....'
            }
        }
    }
}