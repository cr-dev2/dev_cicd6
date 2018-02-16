pipeline {
  agent any
  stages {
    stage('FirstSTG') {
      steps {
		def userInput = input(
			id:'userInput', message: 'Please enter CloudHub UserID and Password', 
			parameters: [
			string(defaultValue: '', description: '', name: 'apusername'), 
			password(defaultValue: '', description: '', name: 'appassword')
			])
        echo ('BRANCH NAME: '+userInput['apusername'])
      }
    }
  }
}