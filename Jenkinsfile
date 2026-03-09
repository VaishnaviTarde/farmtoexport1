pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                git 'https://github.com/VaishnaviTarde/farmtoexport1.git'
            }
        }

        stage('Build') {
            steps {
                echo "Static website - no build required"
            }
        }

        stage('Test') {
            steps {
                echo "No tests for static HTML project"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying website"
                sh 'cp -r * /var/www/html/'
            }
        }

    }
}
