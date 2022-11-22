pipeline {
  agent any 
  parameters {
    string (name:'Greeting', defaultvalue:'Hello', Description:'How should i greet the World?')
  }
  stages {
    stage('example') {
      steps {
        echo "${params.greeting}Welcome to jenkins wrold!"
      }
    }
  }
}
