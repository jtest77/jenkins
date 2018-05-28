pipeline {
    agent { docker { image 'ruby' } }
    stages {
        stage('test_stage'){
            steps {
                sh 'cat /etc/version'
            }
        }
        stage('build') {
            steps {
                sh 'ruby --version'
            }
        }
    }
}
