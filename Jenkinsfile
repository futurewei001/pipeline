
pipeline {
    agent {
        label 'master' 
    }
    tools {
        maven 'apache-maven-3.6.1' 
    }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
