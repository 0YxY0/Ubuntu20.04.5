pipeline {
	agent any

	stages {
		stage('compile') {
			step {
				sh "gcc main.c"
			}
		}
		stage('print') {
			step {
				sh "./a.out"
			}
		}
	}
}
