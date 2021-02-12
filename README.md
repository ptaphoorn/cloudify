# requirements:

1. todo: environments must be scalable, howto update deployment ?
2. todo: Or deploy more than one vm with only one with a public IP.
3. environment is linked to requester in deployment name and resource group name.
4. copy local blueprint are available in git repo as .yaml files
6. todo: hostnames, normal user name
7. location defaults to WestEurope in yaml




 # setup Azure

 1. create app registration, certificates and secrets -> New client secret # save this secret, it's displayed only during creation
 
 2. Access Control (IAM) -> Add role assignment -> Role: Owner, Search <app registration>
	 

# setup Cloudify

Create these secrets in Syetem Resources:
- azure_tenant_id
- azure_subscription_id
- azure_client_id
- azure_client_secret <-- displayed only once during creation of client secret in Azure

In order to remove a deplyment: cancel if required, uninstall, then delete the deployment

Upload bluprint from local .yaml file. Examples are in this repo.


# notes
differences comunity version Cloudify
- not multi tenant
- not multi threadded
- no source code composer
