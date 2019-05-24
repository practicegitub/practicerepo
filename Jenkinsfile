pipeline{
  agent any
  stages{
      stage('build'){
          steps{
              sh "mkdir munich"
          }
      }
      stage('createfile'){
          steps{
           sh 'ls -l'
           dir ('munich') {
                sh"pwd"
           }
      }
  }
}
}
