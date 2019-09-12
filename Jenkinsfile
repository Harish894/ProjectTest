pipline{
agent any
stages{
stage('SCM Checkout'){
      steps{      
	    git 'https://github.com/Harish894/ProjectTest.git'
	
	}
}
	stage('Compile-Package'){
	steps{

		def mvnHome = tool name: 'maven3', type: 'maven'
		sh "mvn package"		
	}
	}
}
}
