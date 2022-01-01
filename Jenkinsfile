pipeline {
    agent any
    
    stages {
        stage ("Initialize") {
            steps {
                echo 'Initialize'
 				  }
                             }
	    stage ("Build") {
            steps {
                echo 'Build'
 				  }
                        }
		stage ('Deploy') {
			steps {
			   echo 'Deploy'
			      }
			             }
	        stage ('Scan') {
			steps {
			   echo 'Scan for vulnerabilities'
			      }
			             }
            }			 
		}  
