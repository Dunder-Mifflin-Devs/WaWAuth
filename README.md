# WaWAuth
## Worth-a-Watch's Authentication and Authorization Microservice

This microservice provides centralized authentication and authorization functionality across all the microservices and ensures secure access can be maintained throughout the app by controlling access to various parts of your application and verifying the identity of users.

*Authentication*: This service handles the process of verifying that users are who they claim to be. It checks credentials, such as usernames and passwords, to grant access to the system.
*Authorization*: After authentication, authorization services determine what actions or resources a user is allowed to access. This involves defining roles, permissions, and access control rules.
*Data*: Manages session tokens, access tokens, user roles, and permissions.
*Security*: Strong security measures are essential, including secure token handling, role-based access control (RBAC), and ensuring that users can only access the parts of the system they are authorized to use.
*Use Case*: When a user logs in, the authentication service verifies their identity, and the authorization service checks whether they have the necessary permissions to perform specific actions or access certain data.
