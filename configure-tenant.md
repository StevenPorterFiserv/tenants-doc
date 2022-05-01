# How to use your space and modify your content.

### Required repository structure:

![repository structure](./images/repo-file-structure.png "repository structure")


### Git branches
There are **three branches** that are required:
  - develop corresponds to [develop/qa environments](https://dev-developerstudio.fiserv.com)
  - stage corresponds to [stage environment](https://stage-developerstudio.fiserv.com)
  - main corresponds to [production environments](https://developer.fiserv.com)

![git branches](./images/gitHubBranches.png "git branches")


### Configurations files 
Files under **config** directory define tenant/product setup, documentation tree, product page data.

![config files](./images/config-files.png "config files")


**config/document-explorer-definition.yaml** defines documetation tree on left navigation panel

![doc tree](./images/docs-tree.png "doc tree")


**config/product-layout.yaml** defines product page content

![product page](./images/product-layout.png "product page")


**config/tenant.yaml** defines product configuration such as 
  - name, 
  - industry or solution. Tenant is able to belong to multiple solutions.
  - API version, 
  - featured branches, 
  - sandbox features, 
  - support contact for tenant specific issues.

![tenant config](./images/tenant-config.png)
![api version](./images/api-version.png)
