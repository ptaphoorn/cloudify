requirements:

# environments must be scalable and linked to requester
# copy local blueprint, multiple vms, related to user, hostnames, normal user name, correct location



~ setup Azure

# create app registration, certificates and secrets -> New client secret # save this secret, it's displayed only during creation
# Access Control (IAM) -> Add role assignment -> Role: Owner, Search <app registration>
	 

~ setup Cloudify

create these secrets in Syetem Resources:
# azure_tenant_id
# azure_subscription_id
# azure_client_id
# azure_client_secret <-- displayed only once during creation of client secret in Azure

remove deplyment: cancel if required, uninstall, then delete the deployment




~ notes
differences comunity version Cloudify
- not multi tenant
- not multi threadded
- no source code composer
