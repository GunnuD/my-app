node {
      stage('SCM Checkout'){
	   git 'https://github.com/GunnuD/my-app'
	  }
	  stage ("Compile-Package"){
	  def mvnHome = tool name: 'Maven', type: 'Maven'
          sh "${mvnHome}/bin/mvn package"'
	  }
	  }
