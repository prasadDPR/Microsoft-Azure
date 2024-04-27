# Microsoft Entra ID: User, Group, and Role-Based Access Management with External Invitations

### Steps to Manage Users, Groups, and Access Control

Architecture Diagram
![Entra ID User, Guest user and Groups](https://github.com/prasadDPR/Microsoft-Azure/assets/121819069/3e6dcd7a-b3b6-4e92-ad3b-1cc8972dcf54)


1. **Sign in to the Azure Portal**:
   - Go to [https://portal.azure.com](https://portal.azure.com) and sign in with your Azure account credentials.

2. **Navigate to Azure Active Directory**:
   - In the left-hand menu, select "Azure Active Directory" or search for it in the search bar.

3. **Create Users**:
   - Click on "Users" under the "Manage" section.
   - Click on "+ New user" at the top.
   - Fill in the required user details.
   - Click "Create" to add the user.
  
![User](https://github.com/prasadDPR/Microsoft-Azure/assets/121819069/c92dea9a-7173-4586-85dc-d369be067200)


4. **Create Groups**:
   - In the Azure Active Directory section, click on "Groups".
   - Click on "+ New group" at the top.
   - Fill in the required group details.
   - Click "Create" to add the group.
  
![group](https://github.com/prasadDPR/Microsoft-Azure/assets/121819069/238eafc0-0fbd-4b2e-a64e-7b1237ba3d67)


5. **Manage Access Control for Users and Groups**:
   - After creating users and groups, navigate to the Azure resource you want to grant access to.
   - Click on "Access control (IAM)" in the left-hand menu.
   - Click on "+ Add role assignment".
   - Select the role you want to assign (e.g., Owner, Contributor, Reader).
   - Choose the user or group you want to grant the role to.
   - Click "Save" to assign the role.
   - Repeat this step for both users and groups as needed.
  
![Other user access](https://github.com/prasadDPR/Microsoft-Azure/assets/121819069/5d3e475b-181c-4a77-b6cf-39789cde0305)
![VM User access](https://github.com/prasadDPR/Microsoft-Azure/assets/121819069/b68582db-46a5-4a80-99ca-26b39b36661b)


7. **Invite External Users**:
   - In the Azure Active Directory section, click on "External identities".
   - Click on "+ Add guest user" at the top.
   - Fill in the email address of the external user you want to invite.
   - Customize the invitation message and set any additional options.
   - Click "Invite" to send the invitation.

8. **Login with User Account**:
   - Open a web browser and go to [https://portal.azure.com](https://portal.azure.com).
   - Enter the username and password of the user account you created earlier.
   - Click "Sign in" to log in to the Azure Portal.
  
![Login as senior user](https://github.com/prasadDPR/Microsoft-Azure/assets/121819069/218fb381-7c94-478d-b10c-4655a1362246)
![Login as other user](https://github.com/prasadDPR/Microsoft-Azure/assets/121819069/6d5d5c20-40f2-4dab-b080-e21a2a1f8f8e)


9. **Monitor and Govern**:
   - Regularly review user and group memberships, access permissions, and audit logs to ensure compliance and security.
