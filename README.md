	1. GitHub Overview 
		a. Review the following Cheat Sheet:
			i. https://rogerdudler.github.io/git-guide/
		b. Create a new folder on the C drive	
      i. cd c:\
			'''mkdir devopsTrainingLabs'''
		c. Create a new repository via the GitHub UI
			i. Click the plus sign on the top right and click "New Repository'
			ii. Name it 'helloWorld'
			iii. Add an MIT License File. 
		d. Fork Lab from Arslan's GitHub
			i. <Add Link>
		e. Clone your forked code from GitHub using CLI
			i. Use a CLI (CMD) and navigate to the C Drive	cd c:\devopsTrainingLabs
			Create a new folder	mkdir helloWorld
			Navigate to the new folder	cd helloWorld
			Clone your forked repo	git clone <repo url>
			
		f. Use VS Code to open your forked version. 
			
	2. Terraform
		a. Azure
			i. Deploy a simple resource. Instructions will be provided: 
					® https://github.com/CardinalNow/TerraformWorkshop/tree/master/challenges
				1) Deploy a Resource Group. 
				2) Log into Azure Portal and verify resources created. 
				3) Modify your code to add another resource and Apply changes.
				4) Delete your resources.
				5) Deploy an Azure VM 
					® https://github.com/CardinalNow/TerraformWorkshop/tree/master/challenges/03-azurevm
		b. Deploy a single resource to GCP
			i. Log into GCP Portal and verify resources created. 
			ii. Modify your code to add another resource and Apply changes.
			iii. Delete your resources.
		c. Deploy a single resource to AWS
			i. Log into AWS Portal and verify resources created. 
			ii. Modify your code to add another resource and Apply changes.
			iii. Delete your resources.
		d. Deploy a complete architecture on GCP
			i. https://medium.com/slalom-technology/a-complete-gcp-environment-with-terraform-c087190366f0
