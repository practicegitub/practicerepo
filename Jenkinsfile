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
              sh "cd muni"
              sh "touch muni"
          }
      }
  }
}
