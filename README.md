# README

## Add and Remove Users Script for Identity Server 
### 1. AddMultipleUsers.jmx
Requirement: With this script anyone can create a role and create multiple users with the new role.

Following will be the user parameters for the add users/role script.

- is_host = Add the server host (ex-localhost)
- is_port = Add the server port (ex-9443)
- adminusername = Add the admin username (ex-admin)
- adminpassword = Add the admin password  (ex-admin)
- adminCredentials = Add the Base64 value of adminusername:adminpassword (ex-YWRtaW46YWRtaW4=)
- usernamePrefix = A username prefix for the usernames. This will append to the username (ex-user)
- noOfTimes = Number of Users needed (ex-500)


### 2. DeleteMultipleUsers.jmx

Requirement: With this script anyone can delete the previously created role and multiple users with that role.

Following will be the user parameters for the delete users/role script.

- is_host = Add the server host (ex-localhost)
- is_port = Add the server port (ex-9443)
- adminusername = Add the admin username (ex-admin)
- adminpassword = Add the admin password  (ex-admin)
- adminCredentials = Add the Base64 value of adminusername:adminpassword (ex-YWRtaW46YWRtaW4=)
- usernamePrefix = The username prefix for the usernames. This will append to the username when deleting (ex-user)
- noOfTimes = number of Users to delete (ex-500)
