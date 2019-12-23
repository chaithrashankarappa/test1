
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
                        echo "M2_HOME = ${M2_HOME}" 
			//bat "mvn clean package"
        
                    }
	    }
	    }
}
	    
