pipeline {
    agent any
    environment {
        CC = 'CC_VALUE'
        PK = credentials('ubuntu_wso2')
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
            steps{
                echo "CC = ${CC}"
                echo "PK = ${PK}"
            }
        }
    }
}
