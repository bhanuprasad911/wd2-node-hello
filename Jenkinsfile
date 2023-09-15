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
    stage ('cpp') {
      steps {
        bat 'g++ 15.cpp -o 15'
        bat '15'
      }
    }
    stage ("java2") {
      steps {
        bat 'java palindrome.java'
      }
    }
  }
}
