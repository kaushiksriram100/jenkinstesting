pipeline {
    agent {
       label 'jenkins-agent'
   }

    stages {
        stage ('Speak') {
            steps {
                sh 'echo "sing" > /tmp/1'
            }
        }
        stage ('Sing') {
            steps {
                sh 'cat /tmp/1; echo "fail"; exit 2'
            }
        }
        stage ('Dancing') {
            steps {
                echo "Hello, dancing!"
            }
        }
    }
}
