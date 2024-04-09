pipeline{
    parameters{
        string(name:"NOD", defaultValue:"Prokas", description: "Jenkins node label where to run")
    }
    //agent{label "${params.NOD}"}
    agent{label "Prokas"}
    stages{
        stage("Test"){
            steps{
                echo 'test step'
            }
        }
    }
}