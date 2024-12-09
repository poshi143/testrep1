pipeline {
  agent any 
  stages {
    stage('working with file IO') {
      steps {
        script {
          //File myfile = new File("/tmp/newfile.txt")
          def file = new File("/tmp/newfile.txt")
          myfile.write("Hello All")
          println "content is ${myfile.text}"
        }
      }
    }
  }
}
