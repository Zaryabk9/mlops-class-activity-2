pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                script {
                    git branch: 'main', url: 'https://github.com/Zaryabk9/mlops-class-activity-2.git'
                }
            }
        }
        
        stage('Set up Python') {
            steps {
                script {
                    // Install Python
                    sh 'apt-get update && apt-get install -y python3 python3-pip'
                }
            }
        }
        
        stage('Install dependencies') {
            steps {
                script {
                    sh 'pip3 ins
