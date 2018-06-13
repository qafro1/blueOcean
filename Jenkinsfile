pipeline {
    agent any
    tools {
        maven 'localMaven'
    }
    stages {
        stage ('Build') {
            steps {
                sh 'make'
                archiveArtifacts artifacts: '**/target/*.war'
            }

        }
    }
}