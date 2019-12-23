
pipeline{
	    agent any
	       tools {
      maven "maven3"
   }

	    stages{
	        stage("gitcheckout")
	        {
	            steps{
	                git 'https://github.com/chaithrashankarappa/test1.git'
	            }
	            
	        }
	        stage("build")
	        {
	        steps{
                         bat "mvn clean package"
        
                    }
	    }
	    }
}
	    
