pipeline {
	agent any
	environment {
		HOME_DIR= "/home/rajuuu"
	}
	stages {
		stage('Build') {
			parallel {
				stage('sub-build1') {
					echo "sub-build1 pipleline paralle"
				}
				stage('sub-build2') {
					echo "sub-build2 pipleline parallel"
				}
			}
		}
	}
}
