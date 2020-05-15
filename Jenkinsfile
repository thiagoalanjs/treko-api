pipeline{
  agent{
    docker{
      image "node:8-alpine"
    }
  }
  stages {
    stage('Build'){
      steps{
        sh "npm install"
      }
    }
  }
  stages{
    stage('Test'){
      steps{
        sh "npm run test:ci"
    }
   }
 }
}
