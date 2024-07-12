pipeline {
    agent any

    stages {
        stage('Hello'){
            steps {
                echo 'Testing..'
            }
        }
        stage('Build') {
            steps {
                    sh 'mvn -B -DskipTests clean package'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}