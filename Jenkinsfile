pipeline {
    
    agent any
    
   stages {
        
        stage('SCM'){
		steps{
			echo "SCM"
			git 'https://github.com/madhav8890/webserver-with-jenkins.git'
		}         
        }
        stage('Build'){
		steps{
			echo "Build"
		}         
        }
        stage('Deploy'){
		steps{
			echo "Deploy"
		}        
        }
   }
}
