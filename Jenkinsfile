pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'uname -a'
                sh '''
                pwd && ls -al
                cd /home
                pwd && ls -al
                '''
            }
        }
    }
}
