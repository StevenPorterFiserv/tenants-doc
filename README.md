# Welcome to the Tenants documentation!

These markdown files will provide all the info you need to get going to onboard into the Developer Studio.

Below are the overall steps you need to follow:

1. Decide your integration levelde: Full Tenant (Open API YAML file, Markdown Documentation), Doc Only Tenant, Linkout Tenant (Link to the Tenant Portal).
1. Get your info together: Open API YAML file, Markdown Documentation, Product Description, who is it for description and 1-3 UseCases/Popular Services.
1. Signup for a free github.com account: Each tenant needs to register into github using their Fiserv email address and create an account. Once an account is created, please provide the username/gitId to Developer studio team/Tenant Advocate.
2. It would help to use Stoplight or Swagger to edit/debug your docs and spec content.
3. A tenant advocate is assigned who would act as a Github admin to help the tenant get started. 
5. Wait for your tenant space to be provisioned.
4. Submit your info to a Tenant Advocate by creating a github issue in github.com/fiserv/support : Minimum Required Documents: Getting started markdown file, API specification file (yaml), 1-3 use case (1 use case with 1 related document and 1 related api)
5. Structure of the Tenant Repository: The Tenant Advacat will create a repository under Fiserv Git account.    
    1.	Assets/ Images- Folders contain raw images, logos, pdf files etc. These are used to link into a markdown file to display on dev studio.
    2.  Config- folder has document explorer definition yaml file, product-layout yaml file, and tenant json file outlining the structure of documentation, doc tree and product page.
    3.  Docs- Contains all markdown files that gets displayed on documentation explorer part of Dev Studio. The documentation is captured in markdown format (.md file) only.
    4.  References- Contains all api yaml files that gets displayed on API explorer part of Dev Studio for one or more version. All API yaml files must contain a version number so that the right yaml is fetched. The same version number must be referenced in the tenant json file
    5.	Docignore files- files to be ignored- examples archived files
6. Read up on how to use your space and modify content: [Configure Tenant](./configure-tenant.md)
7. Add content based on your integration level
8. Once you're happy with your content create another github issue to get deployed into upper environments and production

Refer to the table contents to the right to get more details about each step.

Ok, let's get started!
