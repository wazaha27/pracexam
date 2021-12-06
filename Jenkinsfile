pipeline {
  agent any
  stages {


     stage('Deploy Development') {
      steps {
            bat "mvn clean package deploy -DmuleDeploy "
          
            echo "deploy success"           
      }
    }
  }
}	