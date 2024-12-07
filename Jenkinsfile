pipeline {
	agent any
	stages {
		stage('Hello') {
			steps {
				echo "Hello from DEMO branch"
			}
		}
		stage('print stage') {
			when {
				branch "feature*"
			}
			steps {
				sh 'cat demo.txt'
			}
		}
	}
}
