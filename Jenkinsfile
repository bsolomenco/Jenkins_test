#!groovy
pipeline{
    agent{label 'Prokas'}
    stages{
        stage("Test"){
            steps{
                node("Prokas")
                    echo 'test step'
                }
            }
        }
    }
}