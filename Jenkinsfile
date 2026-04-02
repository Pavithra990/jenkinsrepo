pipeline {
    agent any

    stages {
        stage('Clone Code') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/Pavithra990/jenkinsrepo.git',
                    credentialsId: 'github-credentials'
            }
        }

        stage('Run Script') {
            steps {
                sh 'bash hello.sh'
            }
        }
    }
}
