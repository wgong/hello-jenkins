pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello Jenkins"'
                sh '''
                    echo "Multiline shell steps"
                    whoami
                    hostname
                    pwd
                    ifconfig
                    uname -a
                    ls -lah
                    which python3
                '''
            }
        }
    }
}
