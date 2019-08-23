
pipeline {
    agent {
        label 'master' 
    }
    def mvnHome = tool 'maven3.5.3'
    env.PATH = "${mvnHome}/bin:${env.PATH}"
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
