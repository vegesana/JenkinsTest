pipeline {
	agent any
	environment {
		HOME_DIR= "/home/rajuuu"
	}
	stages {
		stage('Build') {
			parallel {
					stage('sub-build1') {
						steps {
							dir('Pipeline1') {
								echo "sub-build1 pipleline paralle"
							}
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
