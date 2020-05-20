pipeline {
	agent any
	stages {

		stage ('Build') {
			steps {
				echo('Build')
			}
		}

		stage ('Test') {
			steps {
				echo('Test')
			}
		}

		stage ('IntegrationTest') {
			steps {
				echo('IntegrationTest')
			}
		}

	}

	post {

		always {
			echo 'I always run'
		}

		success {
			echo 'I am a success whore'
		}

		failure {
			echo 'Tool 3omrak hatefdal fashel'
		}

	}
}
