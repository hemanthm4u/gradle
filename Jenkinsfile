pipeline {
    agent any
    tools {
        gradle "gradle"
    }
    stages {
        stage('checkout&build') {
            steps {
                git 'https://github.com/hemanthm4u/gradle'
                sh "gradle build"
            }
        }
            }
}
