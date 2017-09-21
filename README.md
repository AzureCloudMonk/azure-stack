# Chef Automate for Azure Stack
Repo to host Chef Automate Marketplace Solution Templates for Azure Stack 

# Deployment Instructions

Logged in as an Azure Stack administrator, use the following command to make your syndicated Chef Automate image available to your tenants:

```
Add-AzsGalleryItem -GalleryItemUri https://github.com/chef-partners/azure-stack/releases/download/1.0.6/chef-software.chef-automateallinone.1.0.6.azpkg
```
