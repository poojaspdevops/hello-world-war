pipeline {
    agent any
    stages {
        stage('parallel stage') {
            parallel {
                stage ('job5'){
                    step{
                        echo'run job5'
                    }
                }
                stage ('job6'){
                    step{
                        echo'run job6'
                    }
                }
                
            }
        }
      
    }
}
