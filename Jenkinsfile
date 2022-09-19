pipeline{
	agent any
	stages {
		stage ('Build') {
			steps {
				sh 'sleep 5'; echo "this is build stage"
			}
		}
		stage ('test') {
			steps {
				sh '''
					sleep 5
					echo "this is test stage"
					
				'''
			}
		}
		stage ('deploy') {
			steps {
				sh '''
					sleep 5
					echo "this is deploy stage"
				'''
			}
		}
		stage ('my-stage') {
			steps {
				sh '''
					sleep 5
					echo "this is my-stage stage"
				'''
			}
		}
	}
}