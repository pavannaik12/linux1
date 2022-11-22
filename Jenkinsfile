pipeline {
  agent any 
  parameters {
    string (name:'Greeting', default value:'Hello', Description:'How should i greet the World?')
  }
  stages {
    stage('example') {
      steps {
        echo "${params.greeting}Welcome to jenkins wrold!"
      }
    }
  }
}
