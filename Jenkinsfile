pipeline {
    agent any
    tools {
        maven 'm3' 
    }
    stages {
        stage('Example') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
