node {
	stage('Clone'){
	git url :'https://github.com/Bintouloo/JenkinsProject'
	}
	stage('Build'){
		sh label:'', script:'javac EmployManagementSystem.java'
	}
	stage('Run'){
		sh label:'', script:'java EmployManagementSystem'
	}
}
