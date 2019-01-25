pipeline {
    agent none

    stages {
        stage('Build') {
            agent {
                docker {
                    image 'elk.copperdale.teknofile.net:8200/ruby:latest'
                }
            }

            steps {
                sh 'ruby -v'
            }
        }
    }
}
