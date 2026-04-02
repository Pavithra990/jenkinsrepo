pipeline {
  agent any

  stages {
    stage('Clone Code') {
      steps {
        git 'https://github.com/your-username/jenkins-demo.git'
      }
    }

    stage('Run Script') {
      steps {
        sh 'bash hello.sh'
      }
    }
  }
}
