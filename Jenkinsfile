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
                sh"touch sample1.txt"
                sh "echo hai sample >> sample1.txt"
                sh"echo addig content >> sample1.txt"
           }
      }
  }
}
}
