pipeline {
    agent {label 'java'}

    stages {
        stage('Clone repo') {
            steps {
                git branch: 'main', url: 'https://github.com/harshagowda09/springboot-app-b17.git'
            }
        }
        stage('build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}

