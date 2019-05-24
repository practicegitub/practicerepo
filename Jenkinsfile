pipeline{
  agent any
  stages{
      stage('build'){
          steps{
              sh "echo hai"
          }
      }
      stage('createfile'){
          steps{
           sh 'ls -l'
           dir ('muni') {
                sh"pwd"
                sh"touch sample.txt"
                def readContent = readFile "sample.txt"
                writeFile file: "sample.txt", text: "$readContent Version=$projectVersion\n"
             echo "${sample.txt}"
           }
      }
  }
}
}
