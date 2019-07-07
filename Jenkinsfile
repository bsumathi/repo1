pipeline {

	agent any

	parameters {
		string description: 'AWS Region (source image region)', name: 'source_ami_aws_region', defaultValue: 'us-west-2'
		string description: 'AWS Lambda Function', name: 'copy_share_aws_function', defaultValue: 'golden-image-mgmt-us-west-2-func'
	}

	stages {
		stage('Checkout SCM Code') {
			steps {
				checkout scm
			}
		}
		
	
		stage('Copy AMI with all regions'){
			steps{
				echo "Step = Copy AMI started"
				echo "Step = Copy AMI completed"

			}
		}

		stage('share AMI with all Accounts'){
			steps {
				echo "Step = Share AMI started"
				echo "Step = Share AMI completed"

			}
		}

	}
}

