pipeline {

    agent {
        node {
            label "My test"
        }
    }

    stages {
        stage('Stage 1') {
            steps {
                script {
                    sh 'echo stage_1'
                }
            }
        }
    }

}