pipeline {
    agent any
    stages {
        stage('Checkout Code') {
            steps {
                echo 'GitHub-la irunthu code-a fetch pandrom...'
                checkout scm
            }
        }
        stage('Test Code') {
            steps {
                echo 'Testing the HTML file...'
                sh 'cat index.html'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying pipeline test success machi!'
            }
        }
    }
}
