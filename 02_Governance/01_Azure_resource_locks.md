# Azure resource locks

**Azure Resource locks** can be used to prevent users from accidentally deleting or modifying resources in Azure.

There are 2 types of locks:

- **CanNotDelete** -- Here autorhized users can still read and modify a resource, but they can't delete the resource.
- **ReadOnly** -- Here authorized users can read a resource, but they can't delete or update a resource.

**Note**: Locks can be applied at the resource level, resource group level or at the subscription level.