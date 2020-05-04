pipeline {

    agent any

    stages {
        stage('Stage 1') {
            steps {
                script {
                    sh 'echo stage_1'
                    }
                }
            }
            stage('stage 2') {
                steps {
                    script {
                        sh 'pwd'
                        sh 'echo "this is stage 2" '
                    }
                }
            }
        }

}