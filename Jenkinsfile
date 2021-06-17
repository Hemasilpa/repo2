
pipeline {

      agent any 
	environment {
		NEW_VERSION == '1.2.1'
	        }
       stages {
	  
	      stage("build") {
          when {
            expression {
               BRANCH_NAME == 'Devlope'
                      }
                }  
		  
		        steps {

				echo "hello my groovy version is ${NEW_VERSION}"
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
