pipeline {
  agent any
  stages {
    stage('FirstSTG') {
      steps {
        def branchInput = input message: 'Please input branch to test against', parameters: [[$class: 'StringParameterDefinition', defaultValue: 'master', description: '', name: 'branch']]
        echo "BRANCH NAME: ${branchInput}"
      }
    }
  }
}