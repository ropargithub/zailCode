pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
        stage('Run Script') {
            steps {
                echo 'Running....'
                sh "chmod +x -R ${env.WORKSPACE}"
                sh './echo_example.sh' x=10 Y=20
            }
        }

    }
}
