pipeline {
    agent any

    stages {
        stage('docker')
        {
            steps {
                sh 'docker build -t abcd2:latest .'
                sh 'docker run -d -p 88:80 --name anji1 abcd2:latest'
            }
        }
    }
  }

