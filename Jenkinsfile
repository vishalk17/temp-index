pipeline{
  agent {
  node {
   label 'master'
   customWorkspace '/mnt/'
  }
  }
/**
  stages {
    stage ('installing httpd'){
      steps {
       sh "sudo yum install httpd -y" 
      }
    }
    stage ('copy html.index to /var/www/html dir'){
      steps{
       sh "cp -r index.html /var/www/html/" 
      }
    }
    stage ('start httpd server'){
      steps{
       sh "service httpd start"
      }
    }
  }
**/
}
