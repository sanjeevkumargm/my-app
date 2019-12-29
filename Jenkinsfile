node{
   def mvn = tool (name: 'maven', type: 'maven') + '/bin/mvn'
   stage('SCM Checkout'){
      git 'https://github.com/sanjeevkumargm/my-app'
   }
   stage('Complile-Package'){
   sh "${mvn} clean package"
   }
 }
      
