# aws_DevAssc_prep

### IAM (Identity and Access Management) Overview - Key Points:

1. **Purpose**:

   - IAM is a global AWS service used to manage users, groups, and permissions.
   - Ensures secure access to AWS resources.

2. **Root Account**:

   - Created by default when setting up an AWS account.
   - Should only be used for initial setup and not shared or used frequently.

3. **Users**:

   - Represent individuals in an organization.
   - Can be assigned to groups based on roles or functions.
   - Users can belong to multiple groups but may also exist outside groups (not best practice).

4. **Groups**:

   - Contain users but not other groups.
   - Example: Developers group (Alice, Bob, Charles), Operations group (David, Edward).

5. **Permissions**:

   - Assigned via **IAM Policies** (JSON documents).
   - Policies define what actions a user or group can perform on AWS services.
   - Example: Allowing access to EC2, Elastic Load Balancer, and CloudWatch for specific actions like `Describe`.

6. **Least Privilege Principle**:

   - Users/groups are granted only the permissions they need.
   - Prevents security issues and unnecessary costs.

7. **Best Practices**:
   - Avoid using root account regularly.
   - Use groups to organize users effectively.
   - Follow least privilege principle to enhance security.

Next steps involve hands-on practice with creating users, groups, and assigning permissions.
