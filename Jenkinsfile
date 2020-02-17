
node {
   stage('SCM Checkout'){
        def mvn = tool (name: 'maven', type: 'maven') + '/bin/mvn'
	url: 'https://github.com/prasadkarri1988/jenkins-cicd'
   }
   
    stage('Mvn Package'){
	   // Build using maven
	   sh "${mvn} clean package"
   }
   
   }
   
