Managing content with Fast Content Creator
==========================================

The **Fast Content Creator** portlet in PRODUCT enables you to quickly
create and save a new document with only one template in a specific
location without accessing **Sites Explorer.** This helps you save a lot
of time when creating a new document.

To use the **Fast Content Creator** portlet, you need to add it to a
specific page first by dragging and dropping the Fast Content Creator
portlet from Page Editor Applications Forms to the main pane. This can
be done when `creating a new
page <#PLFUserGuide.AdministeringeXoPlatform.ManagingPages.AddingNewPage>`__
or `editing an existing
page <#PLFUserGuide.AdministeringeXoPlatform.ManagingPages.EditingPage>`__
or `editing the layout of a
site <#PLFUserGuide.AdministeringeXoPlatform.ManagingSites.EditingSite.EditingLayout>`__.

**Configuring Fast Content Creator**

Hover your cursor over the portlet, then click | pencil | to edit the
portlet.

|image1|

The form with the Edit Mode tab appears.

|image2|

**Details:**

+-----------------------+----------------------------------------------------+
| Field                 | Description                                        |
+=======================+====================================================+
| Location to Save      | Selects the location to save documents or          |
|                       | messages.                                          |
+-----------------------+----------------------------------------------------+
| Select Template       | Selects a template for the document. There are     |
|                       | different input fields corresponding to each       |
|                       | selected template.                                 |
+-----------------------+----------------------------------------------------+
| Custom Save Button    | Changes the label for the "Save" button.           |
+-----------------------+----------------------------------------------------+
| Custom Save Message   | Changes the content of custom message that informs |
|                       | you have just saved a document.                    |
+-----------------------+----------------------------------------------------+
| Redirect              | Allows you to redirect the path in the Redirect    |
|                       | Path field.                                        |
+-----------------------+----------------------------------------------------+
| Redirect Path         | Shows a path to which you will be directed after   |
|                       | clicking **OK** in the confirmation message.       |
+-----------------------+----------------------------------------------------+
| The Action pane       | Adds an action to the document and view actions    |
|                       | added to the document.                             |
+-----------------------+----------------------------------------------------+

Select a specific location to save documents.

**i.** Click | magnifying glass | next to the Location to Save field to
open the Select Location form.

|image4|

**ii.** Select the parent node in the left pane, then click | green tick
| in the Add column to select the child node in the right pane. After
being selected, this location will be displayed on the Location to Save
field. Created documents will be saved in this location.

Select a template which is used to create a new document.

Change the label for the Custom Save button, and the content for Custom
Save Message.

Tick the Redirect checkbox if you want to redirect to the path in the
Redirect Path field after clicking **OK** in the confirmation message.

Add an action to the document by clicking Add to open the Add Action
form. Do the same steps in the `Adding an
action <#PLFUserGuide.ManagingYourDocuments.ExtendingYourActions.ManagingActions.AddingAction>`__
section.

Click Close to quit the form to edit the configuration of **Fast Content
Creator**.

Click | green tick | to save all your changes.

The fast content creator portlet will be shown and allows you to create
content quickly. Here is the added page containing a fast content
creator for the Accessible Media template.

|image7|

**Creating/Viewing content**

**Creating new content**

Go to the page which has the fast content creator portlet.

Fill values in all the fields in the page.

Click a button in the page to accept creating the new document. A
message appears to let you know that the document is created
successfully at the location selected in the Location to Save field.

    **Note**

    The button name is different, basing on the `Custom Save
    Button <#CustomSaveButton>`__ field.

**Viewing content**

After creating a new document by **Fast Content Creator**, you can view
it as follows:

Go to **Sites Explorer.**

Select the drive and the path that you established in the configuration
of **Fast Content Creator.** You will see this document.

.. | pencil | image:: images/common/edit_portlet_icon.png
.. |image1| image:: images/ecms/configure_fcc.png
.. |image2| image:: images/ecms/edit_mode_fcc.png
.. | magnifying glass | image:: images/common/search_icon.png
.. |image4| image:: images/ecms/select_location_form.png
.. | green tick | image:: images/common/select_icon.png
.. | green tick | image:: images/common/save_icon.png
.. |image7| image:: images/ecms/fast_content_creator_page.png
