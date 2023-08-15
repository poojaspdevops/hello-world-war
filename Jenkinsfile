pipeline {
    agent any
    stages {
        stage('parallel stage') {
            steps {
                script {
                    parallel (
                        "job5": {
                            stage('job5') {
                                steps {
                                    echo 'run job5'
                                }
                            }
                        },
                        "job6": {
                            stage('job6') {
                                steps {
                                    echo 'run job6'
                                }
                            }
                        }
                    )
                }
            }
        }
    }
}
