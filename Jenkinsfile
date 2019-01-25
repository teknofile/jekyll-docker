pipeline {
    agent none

    stages {
        stage('Build') {
            agent {
                docker {
                    image 'ruby:latest'
                }
            }

            steps {
                sh 'ruby -v'
            }
        }
    }
}
