pipeline{
  agent any
  stages{
      stage('build'){
          steps{
              sh "mkdir munichl2"
          }
      }
      stage('createfile'){
          steps{
           sh 'ls -l'
           dir ('munich') {
                sh"pwd"
                sh"touch file1"
           }
      }
  }
}
}
