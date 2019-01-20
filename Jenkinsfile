pipeline {
    agent { docker { image 'golang' } }
    stages {
        stage('build') {
            steps {
                echo 'build golang'
                sh 'go version'
            }
        }
    }
}
