## Backend
NodeJS & Express

### Actions Workflow requires the following secrets:
AZURE_CREDENTIALS: {\
    "clientId": "...",\
    "clientSecret": "...",\
    "subscriptionId": "...",\
    "tenantId": "...",\
    "activeDirectoryEndpointUrl": "https://login.microsoftonline.com", \
    "resourceManagerEndpointUrl": "https://management.azure.com/" \
}

Generate an SSH key and store the two parts in:

SSH_PRIVATE_KEY\
SSH_PUBLIC_KEY

SSH_USER: username\
SSH_PORT: port for SSH on virtual machine

LOGIC_APP_URL: The url for the Logic App triggered by the HTTP request