pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Reham244/Cloud_20206134.git'
            }
        }

        stage('Execute Script') {
            steps {
                sh 'chmod +x list_files.sh'
                sh './list_files.sh'
            }
        }
    }
}
