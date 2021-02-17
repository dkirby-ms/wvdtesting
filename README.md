# wvdtesting

Test build to deploy WVD Host pool with VMs created from standard gallery image.

# Prereqs

  * Existing AD domain controller inside an Azure vNet
 
# Deployment

Clone the repo and from the folder you cloned it to run:

```shell
az deployment group create -g <name of your resource group> --template-file daletemplate.json --parameters daleparms.json
```
