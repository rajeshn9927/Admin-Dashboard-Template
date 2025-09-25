pipeline{
	agent any
	stages{
		stage("Deploy to webserver"){
			steps{
				sh '''
					cp -r * /var/www/html/
				'''
			}
		}
	}
}
