# Deploy cmd

Export the variable:

	 export NEW_CLI=2
	 export MyTenant=<MyTenant>
	 export MyToken=<MyToken>
	 export MZ=<MZ-name>
		 

Deploy the configuration:

	cd;cd dynatrace-lab/lab-onboarding;
	./monaco deploy -e=environments.yaml deploy
