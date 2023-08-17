pipeline {
    
    agent any
    
   stages {
        
        stage('SCM'){
		stpes{
			echo "SCM"
			git 'https://github.com/madhav8890/webserver-with-jenkins.git'
		}         
        }
        stage('Build'){
		stpes{
			echo "Build"
		}         
        }
        stage('Deploy'){
		stpes{
			echo "Deploy"
		}        
        }
   }
}
