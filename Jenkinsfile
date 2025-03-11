pipeline {
    agent any
    tools {
        maven 'maven'
    }
    stages {
        stage ("Validate") {
            steps {
                sh 'mvn clean validate'
            }
        }
        stage ("Build") {
            steps {
                sh 'mvn clean build'
            }
        }
    }
}