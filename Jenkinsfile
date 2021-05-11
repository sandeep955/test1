pipeline {
    agent {
        dockerfile true
    }
    stages {
        stage ('Os') {
            steps {
                sh 'cat /etc/os-release'
                sh 'whoami'
                sh 'hostname'
                sh 'pwd'
            }
        }
    }
    
}
