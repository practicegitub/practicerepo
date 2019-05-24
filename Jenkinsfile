pipeline{
  agent any
  stages{
      stage('build'){
          steps{
              sh "mkdir munichl"
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
