# scim-postman
Postman collection for SCIMV1 and SCIMV2 using PingDirectory 8.


SCIM V1 uses basic authentication
SCIM V2 uses Bearer token to authenticate (required for SCIM V2)

In PingDirectory 8.x we support SCIMV2 and SCIMV1.1.  Since the PingDirectory comes with People, these examples use ou=people,dc=example,dc=com and ou=groups,dc=example,dc=com to create, update, search, and delete Directory Objects.

The following things are included in this docment:

1)	Command line to create a Directory 
2)	The dsconfig commands turn on SCIM.  This is included in a dsconfig batch file
3)	ldapmodify commands to create groups and setup the ACI’s
4)	Debug commands you may need to turn on additional logging
5)	Configuration for PingFederate
6)	Postman collection to call the API to show off SCIM V1.1 and SCIM V2
7)	Notes to assist you
8)	Documentation I found useful while testing and debugging
