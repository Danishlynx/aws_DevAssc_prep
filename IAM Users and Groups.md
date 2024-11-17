### Practicing IAM: Creating Users in AWS - Key Points

1. **Accessing IAM**:

   - Search for "IAM" in the AWS console to navigate to the IAM Dashboard.
   - IAM is a **global service**, so no region selection is required.

2. **Why Create Users**:

   - Root account is not recommended for regular use.
   - Create users (e.g., admin users) to manage the account securely.

3. **Creating a User**:

   - Go to the **Users** section and click on "Create User."
   - Provide a **username**
   - Choose to create an IAM user (not Identity Center for simplicity).
   - Set a password:
     - Use auto-generated for others with a "must-change-password" requirement.
     - For personal use, set a custom password and disable "must-change-password."

4. **Assigning Permissions**:

   - Directly assign permissions or use groups.
   - Example:
     - Create a group named **Admin** with **Administrator Access** policy.
     - Add the user to the group.

5. **Review & Tags**:

   - Review the configuration, including username, group membership, and permissions.
   - Tags (optional) add metadata (e.g., department: engineering).

6. **Managing Permissions**:

   - Users inherit permissions from their groups.
   - Example: "Stephane" inherits **Administrator Access** via the "Admin" group.

7. **Signing In**:

   - Use **account ID** or **account alias** (customizable) for the sign-in URL.
   - Signing in as the new IAM user:
     - Use a private browser window for simultaneous sessions (root and IAM user).
     - IAM user login displays "IAM user" in the top-right corner for identification.

8. **Recommendations**:

   - Use IAM users for regular activities instead of the root account.
   - Keep root and IAM user credentials secure to avoid account access issues.

9. **Course Guidance**:
   - Follow instructions for when to use root vs. IAM user as needed.
   - Keep both root and IAM user windows open for practice.
