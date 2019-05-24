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
                sh"touch file"
                sh "echo version >> file"
           }
      }
  }
}
}
