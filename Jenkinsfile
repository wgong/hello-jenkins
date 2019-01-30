pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello Jenkins Pipeline"'
                sh '''
                    echo "Multiline shell steps works"
                    date
                    TZ=Europe/Amsterdam date +%Y-%m-%d:%H%M
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
