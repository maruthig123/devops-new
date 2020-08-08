node {
state('Git Checkout')
  {
'https://github.com/maruthig123/devops-new/'
  }
state('Compile and package')
{
  def mvnHome = tool name: 'maven3', type: 'maven'
  def mvn = "${mvnHome}/bin/mvn"
  sh "${mvn} clean package"
}
}
