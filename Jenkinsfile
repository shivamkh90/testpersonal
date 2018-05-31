pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        cfnUpdate(stack: 'ATG-DMAP-e1-network', url: 'https://s3-eu-west-1.amazonaws.com/atg-dmap-cloudformation/ATG-DMAP-Network.json1', keepParams: 'true')
      }
    }
  }
}