pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Doniaahmed22/PipelineCloudTask.git'
            }
        }
        stage('Execute Script') {
            steps {
                bat './bashFile.bat'
            }
        }
    }
}
