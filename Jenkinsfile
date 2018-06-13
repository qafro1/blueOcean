pipeline {
    agent any
    tools {
        maven 'localMaven'
    }
    stages {
        stage ('Build') {
            steps {
        
                archiveArtifacts artifacts: '**/target/*.war'
            }

        }
    }
}