pipeline {
	agent any

	stages {
		stage('compile') {
			steps {
				sh "gcc main.c"
			}
		}
		stage('print') {
			steps {
				sh "./a.out"
			}
		}
	}
}
