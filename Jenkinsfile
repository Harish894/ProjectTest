pipline{
agent {label 'myfirstpipline'}
stages{
stage('SCM Checkout'){
      steps{      
	    git 'https://github.com/siraj09/maven_repo'
	
	}
}
	stage('Compile-Package'){
	steps{

		def mvnHome = tool name: 'maven', type: 'maven'
		sh "mvn package"		
	}
	}
}
}
