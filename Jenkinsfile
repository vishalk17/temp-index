pipeline{
  agent {
  node {
   label 'master'
   customWorkspace '/mnt/test/'
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
