pipeline {
  agent any
  stages {
    stage('disk-write') {
      steps {
        ws(dir: 'D:\\PerlScripts\\') {
          pwd()
          bat(script: 'perl write-perf-random.pl -esapath=Z:\\ -flen=555m -number=10', returnStatus: true, returnStdout: true)
        }

      }
    }
  }
}