pipeline {
  agent any
  stages {


     stage('Deploy Development') {
      steps {
            bat "mvn clean package deploy -DmuleDeploy "
            // -Dusername=API_1904"
            echo "deploy success"           
      }
    }
  }
}	