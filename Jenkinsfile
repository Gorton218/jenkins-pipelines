pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
        build(job: 'project 1', propagate: true, wait: true)
      }
    }
  }
}