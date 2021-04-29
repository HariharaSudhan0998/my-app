node{
   stage ('SCM Checkout'){
     
   }
   stage('Compile-Package'){
     def mvnHome = tool name: 'Maven-Demo', type: 'maven'
	 sh "${mvnHome}/bin/mvn package"
	 }
   }
