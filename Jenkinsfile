pipeline {

    stages {
        stage('Prepare job definition') {
            steps {
                script {
                    sh 'echo "=============================="'
                    sh 'echo "${WORKSPACE}"'
                    sh 'ls -lth'
                    sh 'echo "$$==============================$$"'
                }
            }
            post {
                always { 
                    cleanWs()
                }
            }
        }
    }
}


