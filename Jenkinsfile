pipeline {
    agent any
    stages {
        stage('clone step') {
            steps {
                sh 'rm -rf hello-world-war'
                sh 'git clone https://github.com/poojaspdevops/hello-world-war.git'
            }
        }
        stage('build') {
            steps {
                sh 'mvn package'
    }
}
    }
}
