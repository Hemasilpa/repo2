
pipeline {

      agent any 
      parameters {
      //string(name: 'VERSION', defaultValue: '', description: 'version to deploy on prod')
      choice(name: 'VERSION', choices: ['1.1', '1.2', '1.3'], description: '')
      BooleanParam(name: 'executeTests', defaultValue: true, description: '')	
	environment {
		NEW_VERSION = '1.2.1'
	        }
       stages {
	  
	      stage("build") {
          when {
            expression {
               params.executeTests
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
