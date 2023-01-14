pipeline{
  agent {
  node {
   label 'master'
   customWorkspace '/mnt/dev/'
  }
  }
  stages {
    stage ("dummy"){
      steps{
        sh "ls"
      }
    }
  }
}
