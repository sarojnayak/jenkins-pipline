node {
	stage ('SCM checkout'){
		git "https://gitlab.com/mbabilo/experitest"
		}
	stage ('Build'){
    	dir("comtest") {
	   sh "mvn clean install"
	}
}
}
