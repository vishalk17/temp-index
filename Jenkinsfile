pipeline{
  agent {
  node {
   label 'master'
   customWorkspace '/mnt/'
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
