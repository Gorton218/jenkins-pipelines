pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
        build(job: 'project 1', propagate: true, wait: true)
      }
    }
    stage('stage 2') {
      steps {
        build(job: 'project 2', propagate: true, wait: true)
      }
    }
  }
}