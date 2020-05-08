pipeline {
  agent any
      stages {
			
		     stage ('Build') {
		        steps {
		           sh '''
			           cd $WORKSPACE
			           echo "Welcome to Build stage"
                 '''
			      }
            }
	     	stage ('Deploy') {
		      steps {
		        sh '''
		         cd $WORKSPACE
             echo "Welcome to Deploy stage"
		         '''
			      }
            }
		
		}
	} 
