pipeline{
	agent any
	tools {
    	jdk 'JDK 21'
    	maven 'Maven 3.9.9'
	}
	stages{
		stage('build'){
			steps{
				bat 'mvn clean package'
			}
		}
	}
}
