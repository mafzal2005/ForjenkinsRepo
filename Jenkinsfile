pipeline {
  agent any
  stages {
    stage('build1') {
      parallel {
        stage('build1') {
          steps {
            sh 'echo "this is build stage one "'
          }
        }
        stage('stage 2') {
          steps {
            sh 'echo "this is a stage 2 for this pipeline "'
          }
        }
        stage('final stage') {
          steps {
            sh '''echo "this is a final stage " 
'''
          }
        }
      }
    }
  }
}