pipeline {
  agent any
  stages {
    stage('FirstSTG') {
      steps {
        input(message: 'Please Enter User Inputs', id: 'LocalUserInputs', submitterParameter: 'CHUSERNAME')
      }
    }
  }
}