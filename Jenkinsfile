node{
   stage ('SCM Checkout'){
     git 'https://github.com/HariharaSudhan0998/my-app.git'
   }
   stage('Compile-Package'){
     def mvnHome = tool name: 'deafult', type: 'maven'
	 sh "${mvnHome}/bin/mvn package"
         sh(script: 'mvn deploy')
	 }
   }
