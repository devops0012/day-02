pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build(job: 'one', wait: true)
        sh 'touch file1'
        echo 'Hello World'
      }
    }

  }
}