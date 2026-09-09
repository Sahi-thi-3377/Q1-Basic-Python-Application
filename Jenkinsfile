pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/Sahi-thi-3377/Q1-Basic-Python-Application.git'
            }
        }

        stage('Build') {
            steps {
                sh 'printf "10\n20\n" | python3 app.py'
            }
        }
    }
}