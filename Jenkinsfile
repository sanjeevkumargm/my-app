node{
   stage('SCM Checkout'){
      git 'https://github.com/sanjeevkumargm/my-app'
   }
   stage('Complile-Package'){
      // Get Maven Home Path
    def maven_home = tool name: 'maven', type: 'maven'
      sh "${maven_home}/bin/mvn package"
   }
 }
      
