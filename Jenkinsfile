#!/usr/bin/env groovy
pipeline {
	agent any
	parameters {
	choices (
		choices: 'Default\nCreate new VM',
		description: '',
		name: 'VM_provisioning')
	}
	/*tools {
		maven 'Default'
        jdk 'Default
	}*/
	stages {
		stage('Create Virtual Machine') {
			when {
				expression { params.VM_provisioning == 'Create new VM'}
			}
		}
	}
}
