pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Doniaahmed22/PipelineCloudTask'
            }
        }
        stage('Execute Script') {
            steps {
                bat './bashFile.bat'
            }
        }
    }
}
