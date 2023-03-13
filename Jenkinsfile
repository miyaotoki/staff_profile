pipeline{
	agent any
	environment{
		staging_server="localhost"
	}
	stages{
		stage('Deploy to Remote'){
			steps{
				//copy php for entire to apache folder
				echo 'copy file to xampp folder ${WORKSPACE}'
				//sh 'scp ${WORKSPACE}/* root@${staging_server}:D:/xampp7/htdocs/staff_profile/'
				
			}
		}
	}
}
