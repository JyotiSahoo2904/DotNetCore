pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'				
                bat 'dotnet publish  -c Release -r win-x64 --self-contained true -o D:\\GITRepository\\Publish\\ -p:PublishReadyToRun=false D:\\GITRepository\\DotNetCore\\WEBAPISERVICE\\WEBAPISERVICE.cspr
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}