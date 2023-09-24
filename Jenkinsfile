pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                 withMaven(maven : 'apache-maven-3.9.4') {
                                   bat'mvn mvn -B -DskipTests clean package'
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