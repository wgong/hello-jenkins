pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello Jenkins Pipeline"'
                sh '''
                    echo "Multiline shell steps works"
                    whoami
                    pwd
                    hostname
                    uname -a
                    ls -lah
                    which python
                    python --version
                '''
            }
        }
    }
}
