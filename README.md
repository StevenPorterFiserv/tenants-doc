# Welcome to the Tenants Documentation!

These markdown files will provide all the info you need to get going to onboard into the Developer Studio.

Below are the steps you need to follow:

1. #### Decide your integration level:
    * Full Service Tenant (Open API YAML file, Markdown Documentation and Live Sandbox Integration)
    * Doc Only Tenant (Open API YAML file, Markdown Documentation and Prism Mock Server Integration)
    * Linkout Tenant (External link to the Tenant Developer  Portal). [Linkout_Tenant](./linkout-tenant.md)

3. #### Get your info together: 
    * Open API Spec file in YAML format (Version 3.0.0 and above)
    * Markdown Documentation, Product Description
    * Who is it for description and 1-3 UseCases/Popular Services.

5. #### Signup for a free github.com account:
    * Each tenant needs to register into github using their Fiserv email address and create an account. Once an account is created, please provide the Github username/registered email address to Developer studio team/Tenant Advocate.

7. #### It would help to use Stoplight or Swaggerhub Editor to edit/debug your docs and spec contents.
     * Swagger at https://fiserv-portal.stoplight.io/
     * Spotlight at https://editor.swagger.io/)
     
5. #### A tenant advocate is assigned who would act as a Github admin to help the tenant get started. 

7. #### Wait for your tenant space to be provisioned.

9. #### Submit your info to a Tenant Advocate by creating a github issue in github.com/fiserv/support :
10. #### Minimum Required Documents: 
    * Getting started markdown file
    * API specification file (yaml)
    * 1-3 use case (1 use case with 1 related document and 1 related api)
    
11. #### Structure of the Tenant Repository: The Tenant Advocate will create a repository under Fiserv Git account.    
    * Assets/ Images- Folders contain raw images, logos, pdf files etc. These are used to link into a markdown file to display on dev studio.
    * Config- folder has document explorer definition yaml file, product-layout yaml file, and tenant json file outlining the structure of documentation, doc tree and product page.
    * Docs- Contains all markdown files that gets displayed on documentation explorer part of Dev Studio. The documentation is captured in markdown format (.md file) only.
    * References- Contains all api yaml files that gets displayed on API explorer part of Dev Studio for one or more version. All API yaml files must contain a version number so that the right yaml is fetched. The same version number must be referenced in the tenant json file
    * Docignore files- files to be ignored- examples archived files
    
12. #### Read up on how to use your space and modify content: [Configure Tenant](./configure-tenant.md)

14. #### Add content based on your integration level

    Once you're happy with your content create another github issue to get deployed into upper environments and production

    Refer to the table contents to the right to get more details about each step.

Ok, let's get started!
