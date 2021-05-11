pipeline {
    agent {
        dockerfile true
    }
    syages {
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
