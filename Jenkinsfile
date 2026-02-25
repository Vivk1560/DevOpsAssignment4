pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Vivk1560/DevOpsAssignment4.git'
            }
        }

        stage('Run Application') {
            steps {
                sh 'node app.js'
            }
        }
    }
}
