node {
	stage('Clone'){
	git url :'https://github.com/steevCpp/JenkinsProject'
	}
	stage('Build'){
		sh label:'', script:'javac EmployManagementSystem.java'
	}
	stage('Run'){
		sh label:'', script:'java EmployManagementSystem'
	}
}
