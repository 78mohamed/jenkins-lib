pipeline {
  agent any

  stages {
    stage('Add Numbers') {
      steps {
        script {
          def addNumbers = load 'addNumbers.groovy'
          def result = addNumbers(2, 3)
          echo "The sum of 2 and 3 is ${result}."
        }
      }
    }
  }
}
