pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                 withMaven() {
                                   bat 'mvn -B -DskipTests clean package'
                                   }
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