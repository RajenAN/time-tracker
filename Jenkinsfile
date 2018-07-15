pipeline {
    agent any
    stages {
        
        stage("chekout") {
            steps {
                git credentialsId: 'jenkins-ssh-key', url: 'git@github.com:RajenAN/time-tracker.git'             
            }
        }
        stage ("build"){
           sh 'echo testing'
        }
    }
}