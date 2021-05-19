pipeline{
agent any
tools{
	maven "Maven3.8"
}
	stages{
	
	stage('Checkout stage'){
		steps{
			script{
			git 'https://github.com/Awsgiri156devops/DevOpsClassCodes.git'
			}
		}
	}
	
	stage('Build stage'){
		steps{
			script{
			sh "mvn package"
			}
		}
	
	}

}
}
