pipeline {
    agent any

    stages{
        stage("Checkout Code"){
            //checkout the repository
            steps {
                git branch: 'main', url: 'https://github.com/DimoLitov/JenkinsSeleniumIDEDemo_30.07'
            }
        }
        stage("Set up .Net"){
            //cinstall dotnet
        }
        stage("Restore dependencies"){
            //cinstall dependencies
        }
        stage("build"){
            //build
        }
        stage("run tests"){
            //run tests
        }
        
        
    }
}