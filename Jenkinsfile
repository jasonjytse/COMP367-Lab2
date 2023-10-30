pipeline {
    agent any
    tools {
        maven '3.8.4'
    }
    stages {
        stage('Build') {
            steps {
                cd 'demo'
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}