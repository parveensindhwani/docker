pipeline {
  agent any
      stages {
			
		     stage ('Build') {
		        steps {
		           sh '''
			           cd $WORKSPACE
			           echo "Welcome to Build stage"
				   my_var="Hello text"
				   echo "my var value is $my_var"
                 '''
			      }
            }
	     	stage ('Deploy') {
		      steps {
		        sh '''
		         cd $WORKSPACE
             echo "Welcome to Deploy stage"
	     echo "var coming from Build stage $my_var"
		         '''
			      }
            }
		
		}
	} 
