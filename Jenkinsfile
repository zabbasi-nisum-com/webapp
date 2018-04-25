//Declarative
Pipeline {
	agent any
	
	stages {
		stage('build'){
			echo 'Building..'
			steps{
				sh “${”MAVEN_HOME}/bin/mvn clean package”	
			}

		}
		stage('Test'){
			echo 'Testing..'
		}
		stage('Deploy'){
			echo 'Deploying..'
		}

	}
}
