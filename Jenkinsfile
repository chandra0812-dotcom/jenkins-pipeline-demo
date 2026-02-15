pipeline {
    agent any

    stages {

        stage('Stage 1 - Print Message') {
            steps {
                echo "This is Declarative Pipeline"
            }
        }

        stage('Stage 2 - Show Date') {
            steps {
                sh 'date'
            }
        }

        stage('Stage 3 - Read File') {
            steps {
                sh 'cat app.txt'
            }
        }
    }
post {
        always {
            echo "Pipeline Finished"
        }
    }
}
