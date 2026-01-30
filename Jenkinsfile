pipeline {
    agent any
      tools {
        maven 'maven'
        jdk 'jdk21'
      }

    stages {
        stage('Build') {
            steps {
                sh 'mvn -B clean install -DskipTests'
            }
        }
    }
}
