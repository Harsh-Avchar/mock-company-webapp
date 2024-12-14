pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    // Run Gradle build
                    sh './gradlew assemble'
                }
            }
        }

        stage('Test') {
            steps {
                script {
                    // Run Gradle tests
                    sh './gradlew test'
                }
            }
        }
    }
}

