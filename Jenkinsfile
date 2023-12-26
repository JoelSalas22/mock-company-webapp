pipeline {
  /*
   * TODO: Implement pipeline stages/steps
   *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
   */
    stages {
    stage('Build') {
    steps {
        echo 'Building..'
        Build: ./gradlew assemble
        }
    }
    stage('Test') {
    steps {
        echo 'Testing..'
        Test: ./gradlew test
        }
    }
//     stage('Deploy') {
//       steps {
//         echo 'Deploying....'
//       }
//     }

}
