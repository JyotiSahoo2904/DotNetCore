pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'				
				bat 'start cmd.exe /c D:\\GITRepository\\DotNetCore\\PublishAll.bat'
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