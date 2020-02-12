#### Amazon AWS Developer Invitation Guide

1. Sign in to your Amazon AWS account
2. Open "Identity and Access Management" (IAM): https://console.aws.amazon.com/iam/home
3. In the left panel, go to Users section: https://console.aws.amazon.com/iam/home#/users
4. Click on "Add User" button
5. Select the User name; Set "Access Type" to "AWS Management Console Access." Select "Autogenerated Password," and select "User must create a new password at next sign-in"; Press "Next: Permissions";
6. Select "Create user without a permissions boundary," and press "Next: Tags";
7. No tags needed (They are optional), so you can just press "Next: Review";
8. Review the info, and move to the next page. It shows a label "Success," and displays the next essential info:

- Sign in URL. Copy it, we will need it for login
- Username (the one you set on step #5). Copy it as well
- Password. Press the "Show" button, and copy it as well.

Please send these 3 values to us, and we will be able to use it for login.

9. Open: https://console.aws.amazon.com/iam/home?#/users
10. You should see that new user in a list. Click on it
11. In Permissions Tab, press Add Permissions button
12. Switch to Attach Existing Policies tab
13. Select "AdministratorAccess". This will give full access to the user, and in the future we should change it, to make it more secure.