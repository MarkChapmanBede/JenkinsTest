pipeline {
  agent any
  
  stages {
    stage("Build"){
      steps {
        sh "touch Build.txt"
      }
    }
    stage("Test"){
      steps {
        sh "ls -lah > test.txt"
      }
    }
    stage("Deploy") {
      steps {
        sh "mv Build.txt Deployed.txt"
        sh "pwd"
      }
    }
  }
}
