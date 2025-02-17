pipeline{
    agent any
    stages{
        stage("Build project"){
            steps{
                bat 'dotnet build'
            }
        }
        stage("Build project"){
            steps{
                bat 'dotnet test'
            }
        }
    }
}