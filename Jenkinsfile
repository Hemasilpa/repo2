
pipeline {

      agent any 
	  
	  stages {
	  
	      stage("build") {
          when {
            expression {
               BRANCH_NAME == 'Devlope'
                      }
                }  
		  
		        steps {

				       echo "good morning"
			        }
				
				}

				
		  stage("test") {
		  
		        steps {

				
			

				echo "good afternoon"
			  }

			
		}
		
		  stage("deploy") {
		     
			    steps {

				     
				    echo "good evening"
			}
	}

   } 
}
