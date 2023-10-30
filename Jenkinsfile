pipeline {
    agent any
    tools {
        maven 'maven'
        jdk 'jdk'
    }
    stages {
        stage('Build') {
            steps {
                sh 'cd demo'
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}