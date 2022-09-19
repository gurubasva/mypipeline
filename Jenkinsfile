pipeline{
	agent none
	stages {
		stage ('Build') {
			agent (label 'node1')
			steps {
				sh 'sleep 5'; echo "this is build stage"
			}
		}
		stage ('test') {
			agent (label 'node2')
			steps {
				sh '''
					sleep 5
					echo "this is test stage"
					
				'''
			}
		}
		stage ('deploy') {
			agent (label 'node1')
			steps {
				sh '''
					sleep 5
					echo "this is deploy stage"
				'''
			}
		}
		stage ('my-stage') {
			agent (label 'master')
			steps {
				sh '''
					sleep 5
					echo "this is my-stage stage"
				'''
			}
		}
	}
}