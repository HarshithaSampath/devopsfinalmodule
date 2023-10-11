pipeline{
  agent any
  stages{
    stage('Deploy'){
      steps{
        echo"Test succesful"
        bat"mvn compile"
      }
    }
    stage('Build'){
      steps{
        echo "build successful"
        but "mvn clean"
      }
    }
    stage('Test'){
      steps{
        echo "Test successful"
        but "mvn test"
      }
    }
  }
}
