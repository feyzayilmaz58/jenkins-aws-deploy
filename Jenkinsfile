pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/feyzayilmaz58/jenkins-aws-deploy.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Build işlemi burada yapılacak'
            }
        }
    }
}
