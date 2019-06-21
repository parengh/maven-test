node{
  stage(`SCM Checkout`){
    git `https://github.com/parengh/maven-test`
  }
  stage(`Compile Package`){
    sh `mvn package`
  }
}
