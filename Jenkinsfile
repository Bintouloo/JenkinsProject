node {
	stage('Clone') {
		git 'https://github.com/steevCpp/JenkinsProject.git'
	}
	stage('Build') {
		sh label:'', script:'javac FacultyBookList_Main.java'
	}
	stage('Run') {
		sh label:'',script:'java   FacultyBookList_Main'
	}
}
