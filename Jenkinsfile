pipeline {
    agent any
    stages {
        stage('Pull Code') {
            steps {
                sh 'mkdir -p /tmp/jenkins-code'
                sh 'cp -r * /tmp/jenkins-code/'
            }
        }
    }
}
