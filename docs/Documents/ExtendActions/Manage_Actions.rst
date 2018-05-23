Managing actions
================

To manage actions, you first need to select the content, then click
|image0| on the Action bar to open the Manage Actions form.

**Adding an action**

Select the Add Action tab.

|image1|

Select one type for your action from the Create Action of Type drop-down
menu, including:

+-----------------------+----------------------------------------------------+
| Type                  | Description                                        |
+=======================+====================================================+
| exo:AddMetadataAction | Adds metadata.                                     |
+-----------------------+----------------------------------------------------+
| exo:autoVersioning    | Adds a version automatically.                      |
+-----------------------+----------------------------------------------------+
| exo:enableVersioning  | Enables versioning.                                |
+-----------------------+----------------------------------------------------+
| exo:taxonomyAction    | Creates categories.                                |
+-----------------------+----------------------------------------------------+

Complete all the fields in the Add/Edit Action form. The Name and
Lifecycle fields are required.

**Details:**

+-----------------------+----------------------------------------------------+
| Field                 | Description                                        |
+=======================+====================================================+
| Name                  | Name of the action. This name is internal to the   |
|                       | JCR explorer.                                      |
+-----------------------+----------------------------------------------------+
| Lifecycle             | Selects the lifecycle for this action. The action  |
|                       | will be executed, depending on the lifecycle:      |
|                       |                                                    |
|                       | -  'User Action': The action is executed when you  |
|                       |    right-click the folder and then select the      |
|                       |    action.                                         |
|                       |                                                    |
|                       | -  'Content Addition': The action will be executed |
|                       |    on a new document, but not on a subfolder when  |
|                       |    the document or the subfolder is created in the |
|                       |    folder to which an action has been added. It is |
|                       |    also applied to a new document in the subfolder |
|                       |    of the folder.                                  |
|                       |                                                    |
|                       | -  'Property Addition': The action will be         |
|                       |    executed on a document when a property is added |
|                       |    to the document.                                |
|                       |                                                    |
|                       | -  'Property Removal': The action will be executed |
|                       |    on a document when a property is removed from   |
|                       |    the document.                                   |
|                       |                                                    |
|                       | -  'Property Modification': The action will be     |
|                       |    executed on a document when a property of the   |
|                       |    document is modified.                           |
|                       |                                                    |
                                                                            
+-----------------------+----------------------------------------------------+

Click Save to commit the action.

All actions of the content are listed in the Available Actions tab.

Once an action is added to the content, it is auto-added to any children
of the selected content.

If an action is added with the lifecycle named 'User Action', it will be
applied to the current content. If an action is added with other
lifecycles, it will be applied to the child content.

    **Note**

    Not all actions are listed in a Right-click menu of the content.
    Some actions can be performed immediately when that action is added.

**Viewing an action**

Select the Available Actions tab.

Click |image2| that corresponds to the action you want to view.

The details will be displayed in the Action Info tab.

**Editing an action**

Select the Available Actions tab.

Click |image3| that corresponds to the action you want to modify.

Edit properties in the Action Form.

Click Save to accept your changes.

**Deleting an action**

Select the Available Actions tab.

Click |image4| corresponding to the action you want to delete, then
click **OK** in the confirmation message.

.. |image0| image:: images/ecms/actions_button.png
.. |image1| image:: images/ecms/add_action_form.png
.. |image2| image:: images/common/view_icon.png
.. |image3| image:: images/common/edit_icon.png
.. |image4| image:: images/common/delete_icon.png
