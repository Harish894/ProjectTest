pipeline{
agent any
	tools {
		maven 'apache-maven-3.6.2'
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
