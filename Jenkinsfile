pipeline {
    agent { docker 'node:14.15.4' }
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