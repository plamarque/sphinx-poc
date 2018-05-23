Managing users
==============

Click |image0| on the top navigation bar, then select Community Manage
Community from the drop-down menu.

You will be redirected to the Users tab. By default, all active users
will be shown in this tab.

|image1|

**Editing user information**

Locate the user you want to edit his information.

Click |image2| corresponding to the user with the information you want
to edit.

Select the Account Info tab to edit main information of the user,
including First Name, Last Name, Display Name, or Email Address.

|image3|

User Name
    The User Name cannot be changed.

Change Password
    The Change Password option allows an administrator to set a new
    password for the selected user. When the Change Password option is
    unchecked, New Password and Confirm Password are hidden. Passwords
    must contain at least 6 characters, including letters, numbers and
    punctuation marks.

For more details on these fields, see
`here <#CreateNewAccountFormDetails>`__.

Select the User Profile tab to edit personal information of the selected
user, including Profile, Home Info, Business Info, and Social Networks
Info (if `OAuth authentication <#PLFAdminGuide.OAuthAuthentication>`__
is configured by your administrator).

-  In Social Networks Info, when clicking the Save button:

   -  If the field of social network username was cleared, the current
      eXo account is unlinked to the new social network username.

   -  If the field of social network username was changed, it should be
      unlinked to the previous social network username and linked to the
      a new (changed) social network username. If the field was left
      blank, it should only be unlinked.

-  You may also switch the default display language for that user by
   selecting another language from the Language field.

Select the User Membership tab to see the group membership information
of the user.

The User Membership tab displays which groups the selected user belongs
to.

To remove a membership type of the use, simply click |image4|.

Click Save to accept your changes.

**Removing a user**

In the Users tab, simply click |image5| in the Action column, then click
**OK** in the confirmation message.

**Activating/Suspending a user**

As of PRODUCT 4.3, the administrator is provided with a new feature for
activating or suspending a user.

To see all suspended users, select All or Suspended from the Status
drop-down menu and click on Search button:

|image6|

For users after being suspended, here are changes on their account that
should be noticed:

**Activity Stream**

-  Their activity stream will not receive any new activity until their
   account is re-activated.

-  The suspended users obviously will not be able to post, so people in
   their Connections list will no longer receive activities from these
   users in their `All Activities <#AllActivitiesFilter>`__ or
   `Connections <#ConnectionsFilter>`__ streams.

-  Their past activities, comments and likes will be remained.

-  Their account will not be listed in the suggestions list when someone
   `mentions <#PLFUserGuide.GettingStarted.ActivitiesInActivityStream.MentioningSomeone>`__.

**People**

-  Their account will be neither listed nor searchable in applications,
   including `My Connections, Everyone <#MyConnectionPage.Tabs>`__,
   `Suggestions <#PLFUserGuide.GettingStarted.SocialIntranetHomepage.IntranetApplications.SuggestionsApplication>`__
   and
   `Invitations <#PLFUserGuide.GettingStarted.SocialIntranetHomepage.IntranetApplications.InvitationsApplication>`__
   applications as usual.

-  They cannot log in, but their profile is still accessible to others,
   so it is possible to `connect <#ConnectViaProfile>`__,
   `disconnect <#DisconnectViaProfile>`__ or
   `revoke <#RevokeViaProfile>`__ an invitation.

**Wiki**

-  Their account will not be listed in the `Wiki
   permissions <#PLFUserGuide.WorkingWithWikis.AdvancedSettings.ManagingPermissions.AddingWikiPermissions>`__
   or `Page
   permissions <#PLFUserGuide.WorkingWithWikis.AdvancedSettings.ManagingPermissions.PagePermissions>`__.

-  They will not receive emails from the `Watching a
   page <#PLFUserGuide.WorkingWithWikis.ManagingContent.ManagingContentChanges.WatchingPage>`__
   feature in Wiki application.

**Calendar**

-  Their account will not be listed when someone `shares their personal
   calendars <#SharingPersonalCalendarDetail>`__ or `grants group
   calendar
   permissions <#PLFUserGuide.ManagingYourCalendars.CreatingCalendar.GroupCalendar>`__.

-  Their account will not be listed when someone `delegates a
   task <#PLFUserGuide.ManagingYourCalendars.SchedulingTask.CreatingNewTask.DetailedTask>`__,
   or `adds participants in an event <#AddingParticipantsToEvent>`__, or
   `views the availability time of participants in an
   event <#ViewingTimeAvailability>`__, or `sends a reminder email for
   an event/task <#CreatingEventReminder>`__.

-  In case they have been involved in tasks/events, once being
   suspended, they will not receive:

   -  Invitation emails from Calendar (after someone modified an event
      where the suspended user was participant already).

   -  Event/Task reminder emails from the Calendar application.

-  Calendars shared by suspended users remain to be available to the
   shared people.

**Documents**

-  Their account will not be listed when someone `adds permissions on
   content <#PLFUserGuide.ManagingYourDocuments.WorkingWithBasicActions.ManagingPermissions.Adding>`__,
   sets permissions on `public
   tags <#PLFUserGuide.AdministeringeXoPlatform.ContentAdministration.WorkingWithExplorer.Tags.SettingPermissionsOnPublicTags>`__
   or `category
   trees <#PLFUserGuide.AdministeringeXoPlatform.ContentAdministration.WorkingWithAdvancedConfiguration.Categories.AddingCategoryTree>`__,
   or
   `adds <#PLFUserGuide.AdministeringeXoPlatform.ContentAdministration.WorkingWithExplorer.Views.ViewsIneXoPlatform.AddingView>`__/`edits
   a
   view <#PLFUserGuide.AdministeringeXoPlatform.ContentAdministration.WorkingWithExplorer.Views.ViewsIneXoPlatform.EditingView>`__.

-  They will no longer receive any email from the `Document Watch
   feature <#PLFUserGuide.ManagingYourDocuments.WorkingWithBasicActions.WatchingUnwatchingDocument>`__.

-  Their documents in the `Personal Document
   drive <#PLFUserGuide.AdministeringeXoPlatform.ContentAdministration.WorkingWithExplorer.Drives>`__
   will be remained.

**Forum**

-  Their account will not be listed when someone sets `topic
   permissions <#PLFUserGuide.BuildingYourForum.RegularUser.Topics.CreatingTopics.SelectingTopicPermissions>`__/`forum
   permissions <#PLFUserGuide.BuildingYourForum.Administrator.ManagingForums.SettingForumPermissions>`__,
   `adds restricted
   audience <#PLFUserGuide.BuildingYourForum.Administrator.ManagingCategories.AddingCategories.AddingRestrictedCategories>`__
   or `grants
   permissions <#PLFUserGuide.BuildingYourForum.Administrator.ManagingCategories.AddingCategories.SettingCategoryPermission>`__
   in forum categories.

-  They will not receive any email from the `Watching
   feature <#PLFUserGuide.BuildingYourForum.RegularUser.Watching>`__,
   `private
   message <#PLFUserGuide.BuildingYourForum.RegularUser.PrivateMessages>`__
   or `my
   subscriptions <#PLFUserGuide.BuildingYourForum.RegularUser.UserSettings.EditingSubscriptions>`__.

**Spaces**

-  Their account will not be listed when someone `invites
   members <#PLFUserGuide.WorkingWithSpaces.ManagingSpaceSettings.ManagingMembers.InvitingMembers>`__
   to join a space.

-  Their account is still available in Space SettingsMembers, but
   impossible to be
   `promoted/demoted <#PLFUserGuide.WorkingWithSpaces.ManagingSpaceSettings.ManagingMembers.PromotingDemotingMember>`__
   or
   `removed <#PLFUserGuide.WorkingWithSpaces.ManagingSpaceSettings.ManagingMembers.RemovingMember>`__.

-  Their account will not be listed or searchable in SpaceMembers.

**Notifications**

-  The suspended users will no longer receive any email or on-site
   notifications.

**Answers**

    **Note**

    Answers is provided as an add-on, so you need to install it first.
    See `here <#eXoAddonsGuide.Answers>`__ for details.

-  Their account will not be listed when someone sets the `category
   permissions <#eXoAddonsGuide.Answers.Moderator.ManagingCategories.AddingCategory>`__.

-  They will no longer receive emails from the `Watching
   feature <#eXoAddonsGuide.Answers.RegularUser.WatchingCategory>`__ of
   Answers.

To suspend a user, switch Active ? button corresponding to this user to
Yes.

    **Note**

    -  Users/groups permitted to access this application can suspend
       users. By default, this permission is granted to the
       *platform/administrator* group.

    -  A user cannot suspend himself, one warning appears if he attempts
       to do this.

    -  The superuser *root* cannot be suspended.

To re-activate a user, simply switch Active ? button corresponding to
this user to No.

.. |image0| image:: images/common/administration_navigation.png
.. |image1| image:: images/gatein/user_management_form.png
.. |image2| image:: images/common/edit_icon.png
.. |image3| image:: images/gatein/edit_account_info_tab.png
.. |image4| image:: images/common/delete_icon.png
.. |image5| image:: images/common/delete_icon.png
.. |image6| image:: images/gatein/disabled_user_list.png
