pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'hello first message'
        timestamps() {
          pwd(tmp: true)
        }

      }
    }
  }
}