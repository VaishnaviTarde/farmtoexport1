pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/VaishnaviTarde/farmtoexport1.git'
            }
        }

        stage('Build') {
            steps {
                echo "Static website - no build required"
            }
        }

        stage('Test') {
            steps {
                echo "No tests required"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying website"
            }
        }

    }
}
