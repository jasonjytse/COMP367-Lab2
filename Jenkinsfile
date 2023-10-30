pipeline {
    agent any
    tools {
        maven 'maven'
        jdk 'jdk'
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