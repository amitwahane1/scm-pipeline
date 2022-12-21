pipeline{
  
 agent{
 
       label{
	   
	       label 'master'
		   customWorkspace '/mnt/project'
	   }
 
 }
 
 stages {
 
   stage('stage-1'){
   
       steps{
	   
	   sh "mkdir test"
	   }
   }
 
 
 stage('stage-2'){
  
  steps {
   
    sh "mkdir folder"
  }
 
 }
 
 }

}
