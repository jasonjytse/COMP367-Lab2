pipeline {
    agent any
    tools {
        maven '3.3.9'
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