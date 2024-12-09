pipeline {
  agent any 
  stages {
    stage('working with files') {
      steps {
        script {
          File file = new File("/tmp/test.txt")
          def lines = file.readLines()
          println "Lines\n ${lines}"
          for(line in lines)
          {
            println line
          }
        }
      }
    }
  }
}

