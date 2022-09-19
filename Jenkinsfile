pipeline{
	agent any
	stages {
		stage ('Build') {
			steps {
				sh 'sleep 10'; echo "this is build stage"
		}
	}
		stage ('test') {
			steps {
				sh '''
					sleep 10
					echo "this is test stage"
				'''
		}
	}
		stage ('deploy') {
			steps {
				sh '''
					sleep 10
					echo "this is test stage"
				'''
		}
	}
		stage ('my stage') {
			steps {
				sh '''
					sleep 10
					echo "this is test stage"
				'''
		
		}
	}
}