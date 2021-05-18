node{
  stage('SCM Checkout'){
    git 'https://github.com/balendrapratap/maven_project'
  }
  
  stage('compile-package'){
   sh 'maven package' 
  }
}
