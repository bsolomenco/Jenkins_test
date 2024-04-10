/*
- Do not allow concurrent builds
- GitHub hook trigger for GITScm polling ? (needs firewal configuration to allow github to PUSH to Jenkins)
- Pipeline script from SCM
    - branch: main
*/
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
                sleep time: 60, unit: 'SECONDS'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                sleep time: 60, unit: 'SECONDS'
            }
        }
    }
}