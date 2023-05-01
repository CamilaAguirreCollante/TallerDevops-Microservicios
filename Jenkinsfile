pipeline {
    agent any
    stages {
        stage('pipeline-td'){
            steps {
                sh 'pylint ./django-project || true'
                sh 'cp -r ./django-project/* /deploy'
            }
        }
    }
}
