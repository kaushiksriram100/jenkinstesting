pipeline {
    agent {
       label 'jenkins-agent'
   }
	parameters {
		string(name: 'OOO', defaultValue: 'xyz', description: 'asdasas') 
	}

    stages {
        stage ('Speak') {
            steps {
                sh 'echo "sing"'
            }
        }
        stage ('Sing') {
            steps {
                sh 'echo "dd"'
            }
        }
        stage ('Dancing') {
            steps {
                echo "Hello, dancing!"
            }
        }
    }
    post {
	success {
		script {
			env.SET = "${params.OOO}/ddd"
			sh "printenv"
		}
		sh 'printenv'
	}

   }
}
