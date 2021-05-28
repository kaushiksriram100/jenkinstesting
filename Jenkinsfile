pipeline {
    agent {
       label 'jenkins-agent'
   }

    stages {
        stage ('Speak') {
            steps {
                exit 2
            }
        }
        stage ('Sing') {
            steps {
                echo "Hello, singing!"
            }
        }
        stage ('Dancing') {
            steps {
                echo "Hello, dancing!"
            }
        }
    }
}
