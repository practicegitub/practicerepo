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
                sh "echo version  >> sample.txt"
           }
      }
  }
}
}
