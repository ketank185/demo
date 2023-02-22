pipeline {
	agent {
		label {
			label "built-in"
			customWorkspace "/opt/assignment1"
		}
	}
	stages {
		stage ("clean workspace"){
			steps {
			cleanWs()
			}
		}
		stage ("build maven project") {
			steps {
			sh "mvn package"
		}
		}
		/* stage ("delpoying of project") {
			sh "cp /opt/assignment1/ "
		} */
}
}
