pipeline {
    agent any
    stages {
        
        stage("chekout") {
            steps {
                git credentialsId: 'jenkins-ssh-key', url: 'git@github.com:RajenAN/time-tracker.git'             
            }
        }
        stage ("build"){
    when { branch "master" }
    steps {
        sh 'echo test'
    }
        }
    }
}