node {
  stage('SCM Checkout'){
      git 'https://github.com/palugunak/maventest'
  }
  stage(Compile-Package){
  sh 'mvn-paclage'
  }
  }
