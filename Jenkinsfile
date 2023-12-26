pipeline {
  /*
   * TODO: Implement pipeline stages/steps
   *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
   */
    stages {
    stage('Build') {
    steps {
        echo 'Building..'
        Build: sh './gradlew build'
        }
    }
    stage('Test') {
    steps {
        echo 'Testing..'
        Test: sh './gradlew test'
        }
    }
//     stage('Deploy') {
//       steps {
//         echo 'Deploying....'
//       }
//     }

}
