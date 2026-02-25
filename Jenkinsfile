pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Vivk1560/DevOpsAssignment4.git'
            }
        }

        stage('CI Test Stage') {
            steps {
                sh 'echo CI/CD Pipeline executed successfully!'
            }
        }
    }
}