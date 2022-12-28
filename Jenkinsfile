pipeline {
    agent any

    stages {
        stage('docker')
        {
            steps {
                sh 'docker build -t vani:latest .'
                sh 'docker run -d -p 90:80 --name srivani vani:latest'
            }
        }
    }
  }
