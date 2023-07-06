def utils = load 'utils.groovy'

pipeline {
  agent any
  
  stages {
    stage('Say Hello') {
      steps {
        node {
          script {
            def sayHello = utils.sayHello
            sayHello('Jenkins')
          }
        }
      }
    }
  }
}
