pipeline{
	agent any
	stages{
		stage("SCM checkout"){
			steps{
			git 'https://github.com/javahometech/my-app', branch: "master"
			}
		stage("maven built"){
			steps{
				sh "MVN clean package" 
			}
		}
	}
}
