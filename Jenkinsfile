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
           dir ('munich') {
                sh"pwd"
                sh"touch file1"
                sh "echo version >> file1"
           }
      }
  }
}
}
