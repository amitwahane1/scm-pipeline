pipeline{
  
 agent{
 
       label{
	   
	       label 'built-in'
		   customWorkspace '/mnt/project'
	   }
 
 }
 
 stages {
 
   stage('stage-1'){
   
       steps{
	   
	   echo "hello all"
	   }
   }
 
 
 stage('stage-2'){
  
  steps {
   
    sh "mkdir folder1"
  }
 
 }
 
 }

}
