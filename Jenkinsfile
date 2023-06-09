withEnv(['AZURE_SUBSCRIPTION_ID=2f7b4261-4172-4aa7-b5ea-a58801629676'])
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
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
def resourceGroup = 'rg_training'
def webAppName = 'WebAppIsha'
