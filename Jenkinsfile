node {
	environment{
	   PATH = "/opt/apache-maven-3.8.2/bin/mvn"
	   }
      stage('SCM Checkout'){
	   git 'https://github.com/GunnuD/my-app'
	  }
	  stage ("Compile-Package"){
	  def mvnHome = tool name: 'Maven', type: 'Maven'
          sh "${mvnHome}/bin/mvn package"'
	  }
	  }
