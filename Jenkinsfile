pipeline{
    parameters{
        string(name:"NOD", defaultValue:"Prokas", description: "Jenkins node label where to run")
    }
    agent{label "${params.NOD}"}
    stages{
        stage("Information"){
            steps{
                script{
                    bat(label:"Information", script:"""
                        dir C:\\ | find "bytes free"
                        whoami
                        ipconfig
                        cmake.exe --version
                    """)
                }
            }
        }
    }
}