pipeline {
    agent any

    stages {
        stage('Clone Code') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/Pavithra990/jenkinsrepo.git'
            }
        }

        stage('Run Script') {
            steps {
                sh 'bash hello.sh'
            }
        }
    }
}
