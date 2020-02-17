
node {
   stage('SCM Checkout'){  
	url: 'https://github.com/javahometech/my-app'
   }
   
    stage('Mvn Package'){
	   // Build using maven
	   def mvn = tool (name: 'maven3', type: 'maven') + '/bin/mvn'
	   sh "${mvn} clean package"
   }
   
   }
   
