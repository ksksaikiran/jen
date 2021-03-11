pipeline{
agent any
  stages{
    stage("git checkout"){
      steps{
      git "https://www.github.com/ksksaikiran/jen.git"
      }
    }
    stage("package"){
      steps{
      sh "mvn package"
      }
    } 
  }
}
