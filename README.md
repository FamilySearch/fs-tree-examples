# fs-tree-examples
This repo contains a Bruno Collection to demonstrate using certain tree-related endpoint in fs-platform-api

**Controlled Edit Trees Bruno Collection**

This is a Bruno Collection covering creating and interacting with a FamilySearch Controlled Edit Tree. See [FamilySearch Developer Portal](https://www.familysearch.org/innovate/developer-portal) for more details.

**Prerequisites**

[Bruno](https://www.usebruno.com/)

[FamilySearch Developer Client Id](https://www.familysearch.org/innovate/apply)

**Getting Started**

To get started

- Clone the git respository holding the collection from the FamilySearch API Workspace from within the FamilySearch API Workspace.

- Import the collection into Bruno 
On the left side of Bruno, click the 3 dots to the right of the Bruno icon and select Import Collection.  Browse to the cloned collection.

- Import the Environment
In the upper right corner of Bruno, drop down the environment list, and click Configure.  In the bottom left corner of the Configuration dialog, click Import and browse to the environments folder in the cloned collection.

Obtain and set an access token

- Go to [https://beta.familysearch.org/platform](https://beta.familysearch.org/platform)
    
    - Press the **Authenticate** button on the Greetings! page. This will lead you through the FamilySearch authentication process.
        
    - On the Congratulations! page, click the blue clipboard button to copy the access token to the clipboard.
        
- In the left side of Bruno, click the Controlled Edit Trees folder and then select the Auth tab.
    
    - Select Bearer Token.
        
    - Edit the access_token field in the variables section by pasting the token you copied from FamilySearch into the Current Value field.
        

You are now configured to be able to execute requests in the collection.

The collection is laid out in sequential order to help you move from request to request with the necessary dependencies available for each request.

Proceed to Step (1-1) Create Group.
