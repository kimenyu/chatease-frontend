pipeline {
  agent any

  stages {
    stage("build") {

      steps {
        sh 'npm install'
        sh 'npm run build'
      }
    }
    stage("test") {
      steps{
        echo 'testing the application....'
      }
    }
    stage("deploy") {
      steps{
        echo 'testing the application....'
      }
    }
  }
}
