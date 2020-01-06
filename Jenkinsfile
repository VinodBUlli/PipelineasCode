
pipeline {
agent any
stages {
  stage ("Build Master"){
   when {
     branch 'master'
   }
   steps {
   echo "deploying master branch"
   
   }
  
  }

  stage("Build dev"){

  when {
     branch 'dev'
  }
  steps{
  echo "Building dev"
  }
  }

  }

  

}





