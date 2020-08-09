node {
stage('Git Checkout')
  {
'https://github.com/javahometech/my-app'
  }
stage('Compile and package')
{
  def mvnHome = tool name: 'maven3', type: 'maven'
  sh "${mvnHome}/bin/mvn clean package"
}
}
