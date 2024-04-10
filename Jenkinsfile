/*
- Block build if certain jobs are running (needs Build Blocker plugin)
    - block on node level
- Do not allow concurrent builds
- Build after other projects are built ("Build")
    - Always trigger, even if the build is aborted
- ? GitHub hook trigger for GITScm polling ? (needs firewal configuration to allow github to PUSH to Jenkins)
- Poll SCM "* * * * *"
- Pipeline script from SCM
    - branch: main
- Lightweight checkout DISABLED
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