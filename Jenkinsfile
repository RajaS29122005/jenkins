pipeline{
  agent any
  stages{
    stage("clone code"){
      steps{
        git branch: 'master',
          url:
          }
    }
    stage("compile code"){
      steps{
        bat "javac demo.java"
          }
    }
    stage("run code"){
      steps{
       bat "java demo"
          }
    }
    
  }
}
