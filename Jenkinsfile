pipeline{
	agent any
	stages{
		stage("checkout code"){
			steps{
				git branch: 'main', url: 'https://github.com/your-username/your-repo.git'
}
}
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
