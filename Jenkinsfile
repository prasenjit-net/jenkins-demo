pipeline {
    agent any
    stages {
        stage('build'){
            steps {
                echo 'Hi'
            }
            post {
                always {
                    echo 'success'
                }
            }
        }
    }
}
