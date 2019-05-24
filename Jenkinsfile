pipeline{
  agent any
  stages{
      stage('build'){
          steps{
              sh "mkdir muni"
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
