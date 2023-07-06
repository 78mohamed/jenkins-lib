library identifier: 'jenkins-shared-library@main', retriever: modernSCM(
        [$class: 'GitSCMSource',
         remote: 'https://github.com/78mohamed/jenkins-lib.git',
         credentialsId: 'github'
        ]


@Library('jenkins-lib') _

pipeline {
  agent any
  
  stages {
    stage('Say Hello') {
      steps {
        sayHello('Jenkins')
      }
    }
  }
}
