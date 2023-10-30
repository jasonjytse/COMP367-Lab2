pipeline {
    agent any
    tools {
        maven 'maven'
        jdk 'jdk'
    }
    stages {
        stage('Build') {
            steps {
                dir('demo'){
                    sh 'mvn -B -DskipTests clean package'
                }
            }
        }
    }
}