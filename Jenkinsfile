node{
  stage('Dev Environment'){
  
  git 'https://github.com/bkmatta/DevOps_Project'
  }
  
  stage('Compil-Package'){
      def  mvnHome= tool name: 'MAVEN_HOME', type: 'maven'  
      sh "${mvnHome}/bin/mvn package"
 }

}
