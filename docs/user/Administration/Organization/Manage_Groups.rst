Managing groups
===============

Select the Groups tab which is used to add, edit or delete a group. You
can also add or delete a user to/from a group and edit the user
membership in the group.

|image0|

By default, all existing groups will be displayed on the left panel. The
right panel shows information of the selected group and of its members
with the Add Member form.

Adding a new group
------------------

Select the path to create a new group by clicking the group from the
left panel or by clicking |image1| if you want to create a group at a
higher level. The selected path is displayed in the breadcrumb bar.

Click |image2| in the left panel.

The Add New Group form will be displayed in the right panel.

|image3|

**Details:**

+--------------------+--------------------------------------------------------+
| Field              | Description                                            |
+====================+========================================================+
| Group Name         | Name of the group that is required and unique within   |
|                    | the portal with its length from 3 to 30 characters.    |
|                    | Only letters, numbers, dash and underscore characters  |
|                    | are allowed for the Group Name field.                  |
+--------------------+--------------------------------------------------------+
| Label              | The display name of the group with any length from 3   |
|                    | to 50 characters.                                      |
+--------------------+--------------------------------------------------------+
| Description        | Description of the group with any length from 0 to 255 |
|                    | characters.                                            |
+--------------------+--------------------------------------------------------+

Fill in the required fields. Once being saved, the Group Name cannot be
edited.

Click Save to accept creating the new group.

    **Note**

    The creator will automatically become the manager of that group. The
    creator's username will be added to the created group with the
    "manager" membership.

Editing/Deleting a group
------------------------

**Editing a group**

Select the group you want to edit in the left panel.

Click |image4| in the left panel to show the Edit Current Group form of
the selected group.

|image5|

Make changes on the fields, except Group Name.

Click Save to commit your changes.

**Deleting a group**

Simply select the group you want to delete in the left panel. Next,
click |image6| and select **OK** in the confirmation message.

    **Note**

    After being deleted, all information related to that group, such as
    users and navigation, is also deleted. You cannot delete the
    mandatory groups, including *Platform, Platform/Administration,
    Platform/Guests, Platform/Users.*

Adding a user to a group
------------------------

Select the group to which you want to add a new user in the left panel.
The Group Info panel with the Add member form will be opened.

|image7|

Enter the exact Username of the user that you want to add to the
selected group (you can add many usernames separated by commas); or
click |image8| to select your desired users from the Select User form.

Select the membership for the users from the Membership drop-down menu.
You can click |image9| to update the memberships list in case of any
changes. See more information of membership types
`here <#PLFUserGuide.AdministeringeXoPlatform.ManagingYourOrganization.ManagingMemberships>`__.

    **Note**

    -  Under the Spaces group, if you select the \* membership for a
       user in any space group, the user will have the right to access
       the corresponding `Space
       Settings <#PLFUserGuide.WorkingWithSpaces.ManagingSpaceSettings>`__.
       Besides, this user will be listed as a manager in the
       `Members <#PLFUserGuide.WorkingWithSpaces.ManagingSpaceSettings.ManagingMembers>`__
       tab as well as an administrator in the `member
       list <#MembersListOfSpace>`__ of the space.

Click Save to accept adding the selected users to the specific group
with the specified membership type.

    **Note**

    By default, the "manager" membership has the highest right in a
    group. A user can have several membership types in a group. To do
    that, you have to use the Add Member form for each membership type.
    The user's membership information is hereafter updated. You can
    check it by opening the Users form and editing the user you just
    added.

Editing a user membership in a group
------------------------------------

Click |image10| in the Action column in the Group Info form. The Edit
Membership form will open.

|image11|

Change the membership of the selected user by selecting another value
from the Membership drop-down menu.

Click Save to complete your changes.

.. |image0| image:: images/gatein/group_management_tab.png
.. |image1| image:: images/common/up_arrow_icon.png
.. |image2| image:: images/common/plus_icon.png
.. |image3| image:: images/gatein/add_new_group_form.png
.. |image4| image:: images/common/edit_icon.png
.. |image5| image:: images/gatein/edit_current_group_form.png
.. |image6| image:: images/common/delete_icon.png
.. |image7| image:: images/gatein/add_member_form.png
.. |image8| image:: images/common/select_users_icon.png
.. |image9| image:: images/common/refresh_icon.png
.. |image10| image:: images/common/edit_icon.png
.. |image11| image:: images/gatein/edit_membership_form.png
