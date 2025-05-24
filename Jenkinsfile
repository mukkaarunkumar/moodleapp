pipeline {
    agent { docker { image 'moodlehq/moodleapp' } }

    stages {
        stage('build') {
            steps {
                sh 'java -version'
                sh 'node -v'
                sh 'npm -v'
            }
        }
    }
}
