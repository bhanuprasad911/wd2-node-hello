pipeline {
  agent any 
  stages {
    stage(version) {
      steps {
        bat 'python --version'
      }
    }
    stage ("hello") {
      steps {
        bat 'python hey.py'
      }
    }
    stage ("java") {
      steps {
        bat 'java Hello.java'
      }
    }
  }
}
