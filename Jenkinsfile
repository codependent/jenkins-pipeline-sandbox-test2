pipeline {
  agent any
  stages {
	stage ('SCM') {
	  steps{
	    script{
	      def scmUrl = scm.getUserRemoteConfigs()[0].getUrl()
	      echo scmUrl
	  	}
	  }
	}
  }
}