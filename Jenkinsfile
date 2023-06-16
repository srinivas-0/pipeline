pipeline {
    agent any
    stages { 
        stage('checkout SCM') {
            steps {
              sh "git pull https://github.com/srinivas-0/pipeline.git"
            }
        }
        stage('Build') {
          steps {
            sh "mvn clean install"
          }
        }
    }
}
