Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker 'go' }
    stages {
        stage('build') {
            steps {
                sh 'go version'
                echo 'hello world'
            }
        }
    }
}
