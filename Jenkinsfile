pipeline {
	agent {
	  dockerfile { 
            label 'agent1'
		  additionalBuildArgs '-t mynginx:${BUILD_NUMBER}
	  }
	}
	stages{
		stage ( 'Example' ){
			steps {
			echo "Hello  World!"
			}
	
		}

	}
}
