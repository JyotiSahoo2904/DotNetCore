pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'	
				bat 'dotnet publish  -c Release -r win-x64 --self-contained true -o D:\\GITRepository\\Publish\\ -p:PublishReadyToRun=false https://github.com//JyotiSahoo2904//DotNetCore//tree//master//WEBAPISERVICE//WEBAPISERVICE.csproj' 
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