pipeline{
	agent any
	tools {								
	  maven 'maven 3.9.9'
	}
	stages{
		stage('build'){
			steps{
				bat 'mvn clean package'
			}
		}
	}
}
