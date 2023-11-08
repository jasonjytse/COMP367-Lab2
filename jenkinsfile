pipeline {
    agent any
    tools {
        maven 'maven'
        jdk 'jdk'
    }
    stages {
        stage('Build') {
            steps {
                dir('comp367'){
                    sh 'mvn -B -DskipTests clean package'
                }
            }
        }
    }
}
