pipeline {
    agent any

    stages {
        stage('git checkout') {
            steps {
                https://github.com/Poojamarne-123/declarative_pipeline.git
            }
        }
        stage('terraform init') {
            steps {
                sh 'terraform init'
            }
        }
        stage('terraform plan') {
            steps {
                sh 'terraform plan'
            }
        }
        stage('terraform apply') {
            steps {
                sh 'terraform apply'
            }
        }
    }
}