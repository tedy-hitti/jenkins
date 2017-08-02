pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh './sayhi.sh'
                sh '''echo
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
