node{
   stage ('SCM Checkout'){
     git 'https://github.com/HariharaSudhan0998/my-app.git'
   }
   stage('Compile-Package'){
     def mvnHome = tool name: 'Maven-Demo', type: 'maven'
	 sh "${mvnHome}/bin/mvn package"
	 }
   }
