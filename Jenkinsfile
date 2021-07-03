node {
	stage ('SCM checkout'){
		git "https://github.com/sarojnayak/jenkins-pipline"
		}
	stage ('Build'){
    	dir("comtest") {
	   sh "mvn clean install"
	}
}
}
