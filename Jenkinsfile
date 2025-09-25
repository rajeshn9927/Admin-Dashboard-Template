pipeline{
	agent any
	stages{
		stage("Deploy to webserver"){
			steps{
				sh '''
					sudo cp -r * /var/www/html/
					sudo systemctl restart nginx
				'''
			}
		}
	}
}
