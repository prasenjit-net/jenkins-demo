pipeline {
    agent any
    environment {
        CC = 'CC_VALUE'
        PK = credential('ubuntu_wso2')
    }
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
        stage('cred check'){
            echo "CC = ${CC}"
            echo "PK = ${PK}"
        }
    }
}
