pipeline {
    agent none

    stages {
        stage('Build') {
            agent {
                docker {
                    image 'ruby:latest'
                    args '-v ${WORKSPACE}:/work'
                }
            }

            steps {
                sh 'ruby -v'
                sh 'ls -alh /work/'
            }
        }
    }
}
