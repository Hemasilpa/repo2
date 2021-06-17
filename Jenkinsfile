
pipeline {

      agent any 
	environment {
		NEW_VERSION = '1.2.1'
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

				
			

				echo "another version added is ${NEW_VERSION}"
			  }

			
		}
		
		  stage("deploy") {
		     
			    steps {

				     
				    echo "good evening"
			}
	}

   } 
}
