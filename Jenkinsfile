
node {
   stage('SCM Checkout'){
	url: 'https://github.com/prasadkarri1988/jenkins-cicd'
   }
   
    stage('Mvn Package'){
	   // Build using maven
	   def mvn = tool (name: 'maven', type: 'maven') + '/bin/mvn'
	   sh "${mvn} clean package deploy"
   }
   
   }
   
