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
                sh '/home/ssingh/scriptShell/echo_example.sh'
            }
        }

    }
}
