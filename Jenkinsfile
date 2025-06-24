pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Dineshvirat123/Isource-.git'
            }
        }
        stage('Build') {
            steps {
                sh 'docker build -t flask-app .'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "No tests added yet."'
            }
        }
        stage('Deploy') {
            steps {
                sh './deploy/ec2_deploy.sh'
            }
        }
    }
}
