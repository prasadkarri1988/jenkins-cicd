
node {
   stage('SCM Checkout'){  
	url: 'https://github.com/prasadkarri1988/jenkins-cicd'
	echo 'checkout done'
   }
   
    stage('Mvn Package'){
	   // Build using maven
	   def mvn = tool (name: 'maven3', type: 'maven') + '/bin/mvn'
	   echo 'mvn package  &&&&&&&&&&&&&&&&&&'
	   sh "${mvn} clean"
   }
   
   }
   
