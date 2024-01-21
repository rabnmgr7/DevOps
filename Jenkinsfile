pipeline {
  agent any
  stages {
    stage('UniiTest') {
      steps {
         echo "Hello, We are inside unittest, running unit test"
      }
     }
    stage('Build') {
      steps {
	 echo "We are inside build stage, building the code now"
	}
	}
    stage('Deploy'){
      steps {
	echo "We are deploy the app"
	}
	}
   }
}
