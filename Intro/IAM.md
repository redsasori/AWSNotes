### IAM: Users & Groups

IAM = Identity and Access Management -> Global Service.
**Root account** created by default, should not be used or shared.
**Users** are people within your organization, and can be grouped.
**Groups** only contain users, not other groups.

Users don't have to belong to a group, and user can belong to multiple groups.

### IAM: Permissions

1. **Users or Groups** can be assigned JSON documents called policies.
2. These policies define the permission of the users.
3. AWS follows the principle of Least Privilege.(Don't give more permissions than a user needs )

![[Pasted image 20250616163539.png]]

### IAM Policy Inheritance

**Audit Team**
**Developers**
**Operations**

### IAM Policies Structure

