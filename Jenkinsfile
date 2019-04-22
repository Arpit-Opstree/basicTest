pipeline {
  agent any
  stages {
    stage('Clone') {
      steps {
        build(job: 'Clone', propagate: true, quietPeriod: 5, wait: true)
      }
    }
  }
}