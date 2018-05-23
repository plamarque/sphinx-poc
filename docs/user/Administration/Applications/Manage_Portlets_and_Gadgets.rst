Managing portlets and gadgets
=============================

Managing portlets and gadgets includes the following actions:

-  `Adding a portlet/gadget to the Application
   list <#PLFUserGuide.AdministeringeXoPlatform.ManagingApplications.ManagingPortletsAndGadgets.AddingPortletGadgetToApplicationList>`__

-  `Activating the Import Applications
   function <#PLFUserGuide.AdministeringeXoPlatform.ManagingApplications.ManagingPortletsAndGadgets.ActivatingImportApplicationsFunction>`__

-  `Viewing/Editing detailed information of a
   portlet/gadget <#PLFUserGuide.AdministeringeXoPlatform.ManagingApplications.ManagingPortletsAndGadgets.ViewingEditingDetailedInformation>`__

-  `Editing a specific
   portlet <#PLFUserGuide.AdministeringeXoPlatform.ManagingApplications.ManagingPortletsAndGadgets.EditingSpecificPortlet>`__

-  `Adding a
   gadget <#PLFUserGuide.AdministeringeXoPlatform.ManagingApplications.ManagingPortletsAndGadgets.AddingGadget>`__

-  `Editing a
   gadget <#PLFUserGuide.AdministeringeXoPlatform.ManagingApplications.ManagingPortletsAndGadgets.EditingGadget>`__

Adding a portlet/gadget to the Applications list
------------------------------------------------

This section shows you how to add a portlet/gadget to the Applications
list on the left panel of the Manage Applications page.

Click Portlet/Gadget on the Tab bar to open a list of portlets/gadgets
respectively.

|image0|

**Details**:

-  Left panel |image1|: The list of portlets/gadget.

-  Right panel |image2|: The information of the portlet/gadget.

-  Breadcrumb bar |image3|: The path of the portlet/gadget.

Click the portlet/gadget which you want to add to the Applications list.

The information of the portlet/gadget is displayed.

Click the Click here to add into categories link to open a form which
allows you to select categories for the portlet.

|image4|

Select your desired categories and click Save to accept adding the
portlet/gadget to the Applications list.

Then, you will see the list of categories to which the portlet/gadget is
added.

|image5|

    **Note**

    In case the portlet/gadget was already added to the Applications
    list, there is no the Click here to add into categories link.

Activating the Import Applications function
-------------------------------------------

The Import Applications function allows you to import all applications
available in the system to the categories on the left panel. However, to
avoid importing unnecessary applications, this function is hidden on the
action bar by default. To show it on the action bar, do as follows:

Go to the `Manage Applications page <#GoToManageApplicationsPage>`__
Edit Page Edit Layout on the Administration bar.

Hover your cursor over the Application Registry portlet, then click
|image6| at the upper left corner of that portlet.

The Edit Mode will be displayed.

Tick the Show "Import Applications" button checkbox, then click Save to
accept the changes.

Click Close to close the Edit Mode form, then click |image7| to quit the
Page Editor page.

The Import Applications button is now shown on the Manage Applications
page.

**Importing portlets and gadgets**

Now you can import default portlets and gadgets into different
categories as follows:

Click |image8| at the right corner on the Action bar.

Click **OK** in the confirmation message to accept importing portlets
and gadgets automatically.

All portlets and gadgets of all categories will be imported and listed
on the left panel.

Viewing/Editing detailed information of a portlet/gadget
--------------------------------------------------------

**Viewing a portlet**

To view details of a portlet/gadget, simply select one portlet/gadget in
the left panel. The details of that portlet/gadget will be shown on the
right panel.

|image9|

**Left panel** |image10|
    All portlets and gadgets grouped by categories.

**Breadcrumb bar** |image11|
    The path of the portlet/gadget.

**Right panel** |image12|
    Details of the portlet: Name, Display Name, Description, and
    information on the Access permission.

**Editing a portlet**

Click |image13| on the top corner of the right panel.

The Edit Application Information form will appear.

Make changes on the fields in the form, except Application Name.

Click Save to commit your changes.

Editing a specific portlet
--------------------------

This section tells you how to access the Edit mode of a portlet and edit
it.

Define your desired portlet to check if this portlet has been existing
in the portal or page. If not, drag and drop it from **Edit Inline
Composer** to the main portal body while `editing the portal's
layout, <#PLFUserGuide.AdministeringeXoPlatform.ManagingSites.EditingSite.EditingLayout>`__
or `editing a
page. <#PLFUserGuide.AdministeringeXoPlatform.ManagingPages.EditingPage>`__

Hover your cursor over your desired portlet, then click |image14| at the
upper left corner of that portlet.

The Edit form will be displayed.

Normally, a portlet has four tabs: Portlet Setting, Select Icon,
Decoration Themes and Access Permission. However, some portlets may also
have Edit Mode and Preferences tabs. For example, IFrame and Dashboard
portlets have the Edit Mode tab where administrators can define the
interface details.

Make changes on fields in the various tabs.

-  The Portlet Setting tab allows you to change values related to
   settings of your selected portlet.

   **In which:**

   +-----------------------+----------------------------------------------------+
   | Field                 | Description                                        |
   +=======================+====================================================+
   | Display Name          | The display name of portlet which cannot be        |
   |                       | changed.                                           |
   +-----------------------+----------------------------------------------------+
   | Portlet Title         | The portlet title with the length between 3 and 60 |
   |                       | characters.                                        |
   +-----------------------+----------------------------------------------------+
   | Width                 | The portlet's vertical size. The value of this     |
   |                       | field must be in numeric format.                   |
   +-----------------------+----------------------------------------------------+
   | Height                | The portlet's horizontal size. The value of this   |
   |                       | field must be in numeric format.                   |
   +-----------------------+----------------------------------------------------+
   | Show Info Bar         | The option enables the information bar to be shown |
   |                       | or hidden. If the Show Info Bar checkbox is not    |
   |                       | selected, Portlet Mode and Window State will not   |
   |                       | be displayed in that portlet.                      |
   +-----------------------+----------------------------------------------------+
   | Show Portlet Mode     | The option enables the portlet mode to be shown or |
   |                       | hidden.                                            |
   +-----------------------+----------------------------------------------------+
   | Show Window State     | The option enables the portlet's window state to   |
   |                       | be shown or not.                                   |
   +-----------------------+----------------------------------------------------+
   | Description           | The brief information of the portlet. The length   |
   |                       | must be between 0 and 255 characters.              |
   +-----------------------+----------------------------------------------------+

-  The Select Icon tab allows you to select an icon for the portlet. By
   clicking Get Default, you do not have to select any icon from the
   list, the suitable icon will be got automatically.

-  The Decoration Themes tab allows you to select a theme for the
   portlet from the themes list. By clicking Get Default, you do not
   have to choose any theme, it will be automatically set.

-  The Access Permission tab allows you to set the access permission on
   the portlet. The portlet can be made public to everyone or restricted
   to specific groups.

       **Note**

       If you set the \* permission to a group, all users of that group
       will have the right to view this portlet, regardless of their
       membership role. See the `Setting Access permission on a
       portlet <#PLFUserGuide.AdministeringeXoPlatform.ManagingPermissions.SettingAccessPermissionOnPortlet>`__
       section for details on how to assign the access permission on a
       portlet.

Click Save And Close to accept your changes, then click |image15| to
quit the Edit Inline Composer/ Page Editor page.

Adding a gadget
---------------

To add a gadget, you first need to access the **Gadget** page by
selecting Gadget on the **Tab** bar of the **Manage Applications** page.

|image16|

You can add a remote gadget using its URL or create a new gadget into
the list.

**Adding a remote gadget**

Click the Add a remote gadget link.

Enter the link of your desired gadget which is in the *.xml* format in
the URL field.

|image17|

Click Add to accept your inputted URL.

The selected gadget will be added to the gadgets list in the left panel
with its details in the right panel.

**Creating a new gadget**

Click the Create a new gadget link.

Enter values in the form.

For example:

Click Save to accept creating your new gadget.

    **Note**

    To add the newly added remote gadget to a specific category, simply
    click the "Click here to add into categories" link at the bottom of
    the right panel. The table listing all categories will appear and
    allow you to select your desired category.

    To update information of the added gadget, simply click |image18| to
    refresh information.

-  You can delete a local gadget using |image19| corresponding to each
   gadget in the left gadgets list.

**Adding a new gadget from Dashboard**

See the `Adding more external gadgets from
Dashboard <#PLFUserGuide.ManagingYourPersonalApplications.ManagingYourDashboard.AddingMoreExternalGadgetsFromDashboard>`__
section for instructions on how to add new gadgets from the dashboard.

Editing a gadget
----------------

Select your desired gadget in the left panel, for example Group
Navigations, then click |image20| located at the header of the **Gadget
Details** page to display the following window.

|image21|

Makes changes in the XML Source Code.

Click Save to commit your changes.

    **Note**

    You cannot change the Name field.

.. |image0| image:: images/gatein/portlet_list.png
.. |image1| image:: images/common/1.png
.. |image2| image:: images/common/2.png
.. |image3| image:: images/common/3.png
.. |image4| image:: images/gatein/add_portlet_to_categories.png
.. |image5| image:: images/gatein/categories_of_portlet.png
.. |image6| image:: images/common/edit_portlet_icon.png
.. |image7| image:: images/common/save_icon.png
.. |image8| image:: images/gatein/import_applications_button.png
.. |image9| image:: images/gatein/application_details.png
.. |image10| image:: images/common/1.png
.. |image11| image:: images/common/2.png
.. |image12| image:: images/common/3.png
.. |image13| image:: images/common/edit_icon.png
.. |image14| image:: images/common/edit_portlet_icon.png
.. |image15| image:: images/Finish_icon.png
.. |image16| image:: images/gatein/gadget_page.png
.. |image17| image:: images/gatein/add_remote_gadget.png
.. |image18| image:: images/gatein/refresh_icon.png
.. |image19| image:: images/common/delete_icon.png
.. |image20| image:: images/common/edit_icon.png
.. |image21| image:: images/gatein/edit_gadget.png
