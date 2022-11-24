



pipeline {
    agent any
    stages {
        stage ('Build') {
            steps {
                echo 'Building ..'
            }
        }
        stage ('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage ('deploy') {
            steps {
                echo 'Deploying..'
            }
        }
            }
        }

pipeline {
    agent any
    parameters {
        string (name: 'Greeting', defaultValue: 'Hello', description: 'How should i greet the world?')
    }
        stages {
            stage ('Example') {
                steps {
                    echo "${params.Greeting} welcome to jenkins world !"
                }
            }
        }
    }
