pipeline {
    agent { 
        docker {
            image 'node:14.15.4'
            args '-p 3000:3000'
        }
    }
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
