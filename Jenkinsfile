node {
  def mvnHome = tool 'maven3'
  stage ("Intial Preparation") {
    bat "echo Preparations are done"
  }
   stage ("Build Code") {
    bat "cd C:/chaitrauser-login-service && ${mvmHome}/bin/mvn clean package"
  }
 }
