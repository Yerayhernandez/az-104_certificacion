# Role based access control

Role-based access control helps you manage access to Azure resources. This is the authorization system that is used to provide fine-grained access control for Azure reources.
When you consider role-based access control, you have to consider 3 aspects:
- Security principal which can either be a User, Group, Service principal or a Managed identity
  - User - This is a profile that you create for an individual in Azure Active Directory
  - Group - This is a set of users created in Azure Active Directory.
  - Service principal - This is a security identity which is created for applications or services.
  - Managed identity - This is an identity that is automatically managed by Azure.
 
 - Definition role itself:
  - The role definition can be an in-built role that is defined in Azure.
  - You can also create your own roles in Azure
  - The basic fundamental roles available in Azure are:
    - Owner - Here the user would have complete access to all resources and also have the right to delegate access to others.
    - Contributor - Here the user can create and manage Azure resources but can't grant access to others.
    - Reader - Here the user can only view Azure resources
    - User Access Administrator: This allows the user to manage user access to Azure resources

  - The scope:
In the scope you could assign roles either at the resource level, so you can assign a role into a virtual machine or to an Azure web app, or you can assign a role at the resource group level, or also you could assign a role at the subscription level.

When you assign a role higher up in the hierarchy, that role also trickles down to the underlying resources.
