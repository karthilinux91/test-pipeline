pipeline {
  agent any
  stages {
    stage('build-stage') {
      steps {
        catchError() {
          build(job: 'write_disk', propagate: true)
        }

      }
    }
  }
}