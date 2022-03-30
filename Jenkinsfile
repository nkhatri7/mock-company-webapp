pipeline {
  /*
   * TODO: Implement pipeline stages/steps
   *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
   */
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Creating Build'
        sh './gradlew assemble'
      }
    }

    stage('Test') {
      steps {
        echo 'Running Unit Tests'
        sh './gradlew test'
      }
    }
  }
}
