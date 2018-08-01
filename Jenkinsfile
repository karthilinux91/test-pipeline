pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        build(propagate: true, job: 'hostname')
      }
    }
  }
}