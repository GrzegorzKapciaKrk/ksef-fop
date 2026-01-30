pipeline {
    agent any
      tools {
        maven 'mvn'
        jdk 'JDK-22'
      }

    stages {
        stage('Build') {
            steps {
                sh 'mvn -B clean install -DskipTests'
            }
        }
    }
}
