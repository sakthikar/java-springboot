pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Build'
            }
        }

    stages {
        stage('Test') {
            steps {
                echo 'Test'
            }
        }
        stages {
        stage('sonarcube') {
            steps {
                echo 'sonarqube'
            }
        }
        stages {
        stage('push to artifactory') {
            steps {
                echo 'push to artifactory'
            }
        }
        stages {
        stage('Deploy to QA') {
            steps {
                echo 'Deploy to QA'
            }
        }
        stages {
        stage('Deploy to prod') {
            steps {
                echo 'Deploy to prod'
            }
        }
    }
    post { 
        failure { 
            echo 'failed'
        }
        success { 
            echo 'success'
        }
       aborted { 
            echo 'aborted'
        }
        always { 
            echo 'always'
        }
    }
}