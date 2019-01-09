pipeline {
    agent any
    stages {
        stage("build") {
            steps {
                echo "building -----------"
            }
        }
        stage("Test") {
            steps {
                echo "testing -----------"
                sh "pwd"
            }
        }
    }
    post {
        always {
          echo "finished -----------"
        }
      success {
          echo "success"
      }
      failure {
          echo "failure"
      }
    }
}
