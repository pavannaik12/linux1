pipeline {
  agent any 
  parameters {
    string(name: 'Greeting', defaultvalue: 'Hello', description: 'How should i greet the World?')
  }
  stages {
    stage('example') {
      steps {
        echo "${params.greeting} Welcome to jenkins wrold!"
      }
    }
  }
}
