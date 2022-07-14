pipeline{
	agent any
	stages{
		stage("SCM checkout"){
			steps{
			git credentialsId: 'Ceejay0007', url: 'https://github.com/Ceejay0007/jinkens-work', branch: "master"
			}
		stage("maven built"){
			steps{
				sh "MVN clean package" 
			}
		}
	}
}
