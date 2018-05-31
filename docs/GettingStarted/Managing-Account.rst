.. _Managing-Account:

Managing Account
~~~~~~~~~~~~~~~~~~
To change your account information, click your display name on the top navigation bar of the site and click Settings from the drop-down menu. 
|image0|
The account settings appears. 
|image1|


Changing your profile information
------------------------------------
1- Select the **Account Profiles** tab. 
2- Change your **First Name**, **Last Name** and **Email**. Your Username cannot be changed. 
3- Click Save button to submit your changes. 

.. note::
The email address changed must be in the valid format. See details about the Email Address format here.

Changing your password
-----------------------
1- Select the **Change Password** tab. 
|image2|
2- Input your current password to identify that you are the owner of this account.
3- Input your new password which must have at least 6 characters.
4- Re-enter your password in the **Confirm New Password** field. 
5- Click **Save** button to accept your changes. 

.. note::
The users who just did their login via the social networks will not have a password defined. 
They should be able to reset a password via their Account Settings or via the Forgot Password feature or ask the administrator to set it (in the Manage Community page). 
Once the password is set, the user can either log in via the login/password or via the social networks.
When the reset password link is clicked:
- An information message is displayed: Reset password guidelines have been sent to you. Please check your mailbox.
- The **Forgot Password** function is executed, and the users receive an email to guide them to change their account password.

Managing your social networks
------------------------------

If your administrator does not integrate OAuth with eXo Platform, you will see one message "No social network available". 
If any social network is integrated, you will see the following that allows you to link/unlink your account to the social networks.
|image3|

- The text fields are read-only. Each has a value when the eXo account is linked with a social network account; otherwise, it is empty.
- A social network username can only be associated with a single eXo account at one time. 
  Hence, if one attempts to link with a username that is already linked to another account, an error message is displayed: This {$Network} username ({$Username}) is already linked to an eXo username. 
  Please enter another one or ask your administrator to unlink it.
- When you click the Unlink button, the link between the social network and the eXo Platform account is reset to blank. Hence, this username can be used to link another eXo account.
