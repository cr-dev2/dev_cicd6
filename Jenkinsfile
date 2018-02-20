pipeline {
  agent any
  stages {
    stage('FirstSTG') {
      steps {
		script {
                def userInput = input(
                 id: 'userInput', message: 'Enter credentials for CloudHub:?', 
                 parameters: [
                 [$class: 'TextParameterDefinition', defaultValue: '', description: 'CloudHub UserName', name: 'CHUserName'],
                 [$class: 'PasswordParameterDefinition', defaultValue: '', description: 'CloudHub Password', name: 'CHPassword']
                ])
                echo ("CloudHub UserName : "+userInput['CHUserName'])
                echo ("CloudHub Password : "+userInput['CHPassword'])

			}
      }
    }
  }
}