pipeline {
    agent any

    stages {
        // Stage 1: SCM (Source Control Management)
        stage('SCM') {
            steps {
                echo "git pull my code step1"
                git 'https://github.com/kumarshuklaankit1998-star/simple-java-maven-app.git'
                // In a real scenario, you'd use: checkout scm
            }
        }

        // Stage 2: Test
        stage('Test') {
            steps {
                echo "running automated tests..."
                echo "test step 1: unit testing"
                echo "test step 2: linting"
            }
        }

        // Stage 3: Deploy
        stage('Deploy') {
            steps {
                echo "deploying my code"
            }
        }
        // Stage 4: Deploy to prod
        stage('Deploy Prod') {
            steps {
                echo "deploying my code to prod"
            }
       }

    }
}
