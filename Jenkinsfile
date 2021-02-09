pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'uname -a'
                sh '''
                node --version
                npm --version
                pwd && ls -al
                cd /home
                pwd && ls -al
                '''
            }
        }
    }
}
