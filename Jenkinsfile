pipeline {
  agent any 
  parameters {
    string(name: 'GREETING', defaultValue: 'Hello', description: 'How shall we greet the world?')
  }
  stages {
    stage('example') {
      steps {
        echo "${params.greeting} Welcome to jenkins wrold!"
      }
    }
  }
}
