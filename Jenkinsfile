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
                sh"touch hema"
                sh "echo version := \\\"1.0.${env.BUILD_ID}\\\" >> hema"
           }
      }
  }
}
}
