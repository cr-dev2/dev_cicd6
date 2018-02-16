pipeline {
  agent any
  stages {
    stage('FirstSTG') {
      steps {
        input(message: 'Please Enter User Inputs', id: 'LocalUserInputs', submitterParameter: 'CHUSERNAME', parameters: [string(defaultValue: '', description: '', name: 'apusername'), password(defaultValue: '', description: '', name: 'appassword')])
		echo "UserName is: LocalUserInputs['apusername']"
      }
    }
  }
}