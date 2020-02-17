
node {
   stage('SCM Checkout'){
	url: 'https://github.com/prasadkarri1988/jenkins-cicd'
   }
   
    stage('Mvn Package'){
	   // Build using maven
	   
	   sh "${mvn} clean package deploy"
   }
   
   }
   