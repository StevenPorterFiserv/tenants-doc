# How to use your space and modify your content.

### Required repository structure:

![repository structure](https://github.com/Fiserv/tenants/blob/main/images/repo-file-structure.png "repository structure")


### Git branches
There are **three branches** that are required:
  - develop corresponds to [develop/qa environments](https://dev-developerstudio.fiserv.com)
  - stage corresponds to [stage environment](https://stage-developerstudio.fiserv.com)
  - main corresponds to [production environments](https://developer.fiserv.com)

![git branches](https://github.com/Fiserv/tenants/blob/main/images/gitHubBranches.png "git branches")


### Configurations files 
Files under **config** directory define tenant/product setup, documentation tree, product page data.

![config files](https://github.com/Fiserv/tenants/blob/main/images/config-files.png "config files")


**config/document-explorer-definition.yaml** defines documetation tree on left navigation panel

![doc tree](https://github.com/Fiserv/tenants/blob/main/images/docs-tree.png "doc tree")


**config/product-layout.yaml** defines product page content

![product page](https://github.com/Fiserv/tenants/blob/main/images/product-layout.png "product page")


**config/tenant.yaml** defines product configuration such as 
  - name, 
  - industry or solution. Tenant is able to belong to multiple solutions.
  - API version, 
  - featured branches, 
  - sandbox features, 
  - support contact for tenant specific issues.

![tenant config](https://github.com/Fiserv/tenants-doc/blob/main/images/tenant-config.png)
![api version](https://github.com/Fiserv/tenants-doc/blob/main/images/api-version.png)
