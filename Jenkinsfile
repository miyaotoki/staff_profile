pipeline{
	agent any
	environment{
		app_folder="D:/xampp7/htdocs/staff_profile/"
	}
	stages{
		stage('Deploy to Remote'){
			steps{
				//copy php for entire to apache folder
				echo 'copy file to xampp folder'
				echo "${WORKSPACE}"
				//sh 'scp ${WORKSPACE}/* root@${staging_server}:D:/xampp7/htdocs/staff_profile/'
				sh 'xcopy ${WORKSPACE} ${app_folder}'
			}
		}
	}
}
