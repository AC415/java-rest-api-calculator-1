pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git 'https://github.com/AC415/java-rest-api-calculator-1.git'
                sh './mvnw clean compile'

            }
        }
    }
}