pipeline {
    agent any
    stages {
        
        stage("build") {
            steps {
                git credentialsId: 'jenkins-ssh-key', url: 'git@github.com:RajenAN/time-tracker.git'
                sh 'echo test'                
            }
        }
    }
}