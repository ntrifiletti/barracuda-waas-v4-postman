## Barracuda Web-Application-Firewall-as-a-Service (WaaS)
## Postman | API REST v4 Collection ##
## Introduction
The WaaS_API_v4.postman_collection.json template in this repository is pre-loaded with documented REST v4 API calls for the Barracuda WAF-as-a-Service platform (Waas).

These templates are useful when building,testing and publishing API v4 calls related to Barracuda Waas APIs. The current "Swagger" spec is OAS3.0. 

Additional API documentation can be found on the [Barracuda Swagger/OpenAPI Spec v4 Website](https://api.waas.barracudanetworks.com/v4/swagger/#/)

![image](https://github.com/ntrifiletti/waas-postman/assets/60154709/d7afc92f-ca47-405f-bffc-602a6f339e8d)

## Install Postman client or use the free web-based version
What is Postman? 
Postman is an API platform for building and using APIs. Postman simplifies each step of the API lifecycle and streamlines collaboration so you can create better APIs—faster.
[Postman Website Download ](https://www.postman.com/downloads/)

## Import into Postman
1. Github | Copy all of the raw code for [WaaS_API_v4.postman_collection.json](https://github.com/ntrifiletti/barracuda-waas-v4-postman/blob/main/WaaS_API_v4.postman_collection.json) into your clipboard.
2. Postman | Open Postman and Click "Import" in the Postman Workspace of your choosing. Paste the contents of your clipboard into the to bar.
3. Click Import as Copy (Recommended) to create the Collection. 
4. Postman | Navigate to the Top-level of the Collection Overview tabs and [change your Authorization type](https://learning.postman.com/docs/sending-requests/authorization/specifying-authorization-details) and [variables](https://learning.postman.com/docs/sending-requests/variables/) to match your Waas API environment.
5. Postman | Click Send to initiate API calls.
6. Postman |Verify the Response Body and Status Codes for succesful transactions.

## Security Hardening
1. Postman | Import the security hardending json collection and import into your Postman
2. Modify the Authorization and Variable to point to your target WaaS Application name
3. Postman | Right click on the Top-level folder PATCH and Run Collection on target
4. The API calls will automatically security harden the application for optimized protection. 

## Useful Tips
The authorization and variables will need to be configured specific to your Postman environments!
Please restart your Postman client if Authorization token does not allow you access. 








