
pipeline {
agent any
stages {
  stage ("Build Master"){
   when {
     Branch: master
   }
   steps {
   echo "deploying master branch"
   
   }
  
  }

  stage("Build dev")

  when {
     Branch: dev
  }
  steps{
  echo "Building dev"
  }

  }

  

}





