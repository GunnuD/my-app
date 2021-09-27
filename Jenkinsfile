node {
      stage('SCM Checkout'){
	  tool name: 'Maven', type: 'maven'
	  git 'https://github.com/GunnuD/my-app'
	  }
	  stage ('Compile-Package){
	  sh 'mvn package'
	  }
	  }
