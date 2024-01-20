pipeline{

agent { node { label 'workstation' }


stages{

  stage('build'){
    steps{
       sh 'npm install'
       echo 'build'
    }
}
  stage('unit test'){
      steps{
        echo 'unit test'
        // sh 'npm test'
      }
  }
  stage('code analysis'){
      steps{
        echo 'code analysis'
      }
  }

  stage('security scans'){
      steps{
        echo 'security scans'
      }
  }

  stage('artifact creation'){
      steps{
        echo 'artifact creation'
      }
  }
}



}