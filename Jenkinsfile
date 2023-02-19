pipeline {
	agent any
	environment {
		HOME_DIR= "/home/rajuuu"
	}
	stages {
		stage('Build') {
			parallel {
				dir('Pipeline1') {
					stage('sub-build1') {
						steps {
							echo "sub-build1 pipleline paralle"
						}
					}
					stage('sub-build2') {
						steps {
							echo "sub-build2 pipleline parallel"
						}
					}
				}
			}
		}
	}
}
