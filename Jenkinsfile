pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Goodbye') {
            steps {
                echo 'Goodbye World'
            }
        }
        stage('pwsh Hello') {
            steps {
                powershell 'Write-Output "Hello PowerShell!"'
            }
        }
    }
}
