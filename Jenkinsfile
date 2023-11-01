pipeline {
  agent any
  stages {
    stage('1') {
      steps {
        build(job: 'test_blue_ocean', waitForStart: true, wait: true, quietPeriod: 1)
      }
    }

  }
}