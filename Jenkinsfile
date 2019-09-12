pipeline{
agent any
	tools {
		maven 'maven3'
	}
stages{
stage('SCM Checkout'){
      steps{      
	    git 'https://github.com/Harish894/ProjectTest.git'
	
	}
}
	stage('Compile-Package'){
	steps{
		
		sh "mvn package"		
	}
	}
}
}
