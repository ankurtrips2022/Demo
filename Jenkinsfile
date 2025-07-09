pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'build'
            }
        }
        stage('Change') {
            steps {
               snDevOpsChange  changeRequestDetails: '{ "attributes": {"chg_model":{"name":"DevOps"} }}'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'deploy'
            }
        }
    }
}
