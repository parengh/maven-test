
node {
  def mvn = tool (name: 'maven3', type: 'maven') + '/bin/mvn'
  stage('SCM Checkout'){
        git 'https://github.com/parengh/maven-test'
  }
  
  stage('Compile Package'){
    sh "${mvn} clean package"
  }
}
