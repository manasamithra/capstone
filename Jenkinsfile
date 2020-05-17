pipeline {
	agent any
	stages {
		stage('Create conf file cluster') {
			steps {
				withAWS(region:'us-west-2', credentials:'capstone') {
					sh '''
						aws eks --region us-west-2 update-kubeconfig --name capstonecluster
					'''
				}
			}
		}

	}
}
