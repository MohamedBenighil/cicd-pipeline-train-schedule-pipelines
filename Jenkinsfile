pipeline {
    agent any
    triggers {
      pollSCM('') // Enabling being build on Push
    }

    stages {
        stage('Build') {
            steps {
                sh './gradlew build'
            }
        }
    }
}
