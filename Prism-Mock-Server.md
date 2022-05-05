There are couple of steps that you need to follow for the prism mock server to work.
 
Add example request and responses in your openapi spec file so that prism mock server can validate your request payload and then return the correct mock response depending on that example. Below is such an instance. On the left hand side is a sample of how to add examples in your spec file and right hand side screenshot explains how it gets mapped on our UI.
 
  Upload the image.

    
 
 
We use Stoplight Prism Mock server and you can read their documenation from here: https://meta.stoplight.io/docs/prism/ZG9jOjYx-overview . You could also install it and run it locally using the below commands and test it in your local before pushing your changes to GitHub.
For installation you can run this command: npm install -g @stoplight/prism-cli
Once successfully installed you can run this: prism mock <your yaml file name>
 
Finally once you are done updating the spec files please let us know we would need to setup up an actual mock server for you J and enable the Run Button as well.
