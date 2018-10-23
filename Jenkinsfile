pipeline {
    agent any 
    stages {
        stage('---Clean----') { 
            steps {
                
				sh "sudo mvn clean"		
					
            }
        }
        stage('---Test---') { 
            steps {
                sh "sudo mvn test"
            }
        }
        stage('---Package---') { 
            steps {
                sh "sudo mvn package"
            }
        }
    }
}
