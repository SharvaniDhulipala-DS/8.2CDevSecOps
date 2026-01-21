pipeline {
    agent any
    stages {
        stage('Build') { steps { echo 'Build code using npm or Maven' } }
        stage('Unit & Integration Tests') { steps { echo 'Run unit and integration tests' } }
        stage('Code Analysis') { steps { echo 'Run code analysis using ESLint or SonarScanner' } }
        stage('Security Scan') { steps { echo 'Run security scan using npm audit' } }
        stage('Deploy to Staging') { steps { echo 'Deploy to staging server' } }
        stage('Integration Tests on Staging') { steps { echo 'Run integration tests on staging' } }
        stage('Deploy to Production') { steps { echo 'Deploy to production server' } }
    }
}


