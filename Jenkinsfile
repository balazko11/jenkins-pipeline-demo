pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Cloning repo...'
                checkout scm
            }
        }
        stage('Run Script') {
            steps {
                echo 'Running hello.sh'
                sh 'chmod +x hello.sh && ./hello.sh'
            }
        }
    }
}
