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
                echo 'Build aşaması: Web sitesi dosyaları hazırlanıyor...'
            }
        }

        stage('Deploy to AWS (Simulated)') {
            steps {
                echo 'Deploy aşaması: AWS S3 bucketına gönderiliyor (simülasyon)...'
                echo 'Dosya: index.html'
                echo 'Hedef: https://feyza-website-bucket.s3.amazonaws.com/index.html (örnek link)'
            }
        }
    }
}
