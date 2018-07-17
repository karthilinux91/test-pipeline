pipeline {
  agent any
  stages {
    stage('build-stage') {
      steps {
        catchError() {
          build(quietPeriod: 5, wait: true, job: 'build')
        }

      }
    }
  }
}