pipeline {
     agent {
	 label {
	     label "built-in"
         customWorkspace "/mnt/pipeline"	 
	 }
	 }
	 stages {
	     stage ("create-file1"){
		 steps {
		 sh "touch file1" 
		      }
		     }
	     stage ("create-file2") {
		 steps {
		 dir ("/data/wsp2") {
		 sh "touch file2"
		        }
		       }
		 
		    }
	 }

}
