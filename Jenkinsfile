pipeline{
  agent {
  node {
   label 'master'
   customWorkspace '/mnt/main/'
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
