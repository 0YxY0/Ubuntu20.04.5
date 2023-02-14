pipeline {
	agent any

	stages {
		stage('compile') {
			steps {
				gcc main.c
			}
		}
		stage('print') {
			steps {
				./a.out
			}
		}
	}
}
