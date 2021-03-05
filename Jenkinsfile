pipeline{
agent any
  stages{
    stage("git checkout"){
      steps{
      git "https://github.com/ksksaikiran/jen.git"
      }
    }
    stage("package"){
      steps{
      sh "mvn package"
      }
    } 
  }
}
