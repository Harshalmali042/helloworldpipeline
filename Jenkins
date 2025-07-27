pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git branch: 'main', url: 'https://github.com/Harshalmali042/helloworldpipeline.git'
            }
        }

        stage('Run Script') {
            steps {
                sh 'python3 helloworld.py'
            }
        }
    }
}
