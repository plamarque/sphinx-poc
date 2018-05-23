Content Types
=============

Namespace registry
------------------

The namespace is a prefix in the node type name. It enables you to
create node types without fearing any conflict with existing node types.
The registry helps you manage the namespaces used in the system.

Select Content TypesNamespace Registry to open the Namespace Registry
form.

|image0|

**Register a namespace**

Click Register on the Namespace Registry form to register a new
namespace.

|image1|

Enter the value for the Namespace Prefix field that is required.

Enter the value for the URI field which must be unique and required.

    **Note**

    The namespace must not contain special characters, such as
    !,@,#,$,%,&,\*,(,).

Manage node types
-----------------

This function is used to control all node types in PRODUCT.

|image2|

**View node types**

Click | [ Glass icon ] | that corresponds to the node you want to view.
The View Node Type Information form will appear.

|image4|

Click Close to exit this form.

**Add a node type**

Open the Add/Edit Node Type Definitions form by clicking Add on the
**Manage Node Type** page.

|image5|

Select a namespace for the node.

Enter a name in the Node Type Name field. This field is mandatory and
its value must be unique.

    **Note**

    The name must not contain special characters, such as
    !,@,#,$,%,&,\*,(,).

Select a value for the Is Mixin Type field.

-  True: This node is Mixin type.

-  False: This node is not Mixin type.

Select a value for the Orderable Child Nodes field.

-  True: Child nodes are ordered.

-  False: Child nodes are not ordered.

Enter a value for the Primary Item Name field.

Click | [ Plus icon ] | to add more parent types in the Super Types
field.

-  Property Definitions: List all definition names of the Property tab.

-  Child Node Definitions: List all definition names of the Child Node
   tab.

Click Save to accept adding a new node type, or Save as Draft to save
this node type as draft.

**Export Node Types**

Open the Export Node Types form by clicking the Export button at the
bottom of the **Manage Node Type** page.

|image7|

Click Uncheck all if you do not want to export all node types. After
clicking Uncheck all, this button becomes the Check all button.

Select nodes that you want to export by ticking the checkboxes.

Click the Export button in this form.

Select the location in your device to save the exported node.

    **Note**

    You must select at least 1 node type to be exported. If you do not
    want to export the node, click Cancel to quit this pop-up.

**Import Node Types**

Open the Import Node Type From XML File form by clicking the Import
button at the bottom of the **Manage Node Type** page.

|image8|

Click Browse... to upload a file.

    **Note**

    You must upload an XML file. This file is in the node type's format.

Click the Upload button.

    **Note**

    If you want to upload another file, click |image9| to delete the
    file which has just been uploaded, then upload other files.

Tick the checkboxes corresponding to the nodes that you want to import.

Click Import to complete importing a node type.

.. |image0| image:: images/namespaceregistry.png
.. |image1| image:: images/namespaceregistrationform.png
.. |image2| image:: images/themanagenodetypeform.png
.. | [ Glass icon ] | image:: images/Glass_icon.png
.. |image4| image:: images/viewnodetypeinformation.png
.. |image5| image:: images/addnodetype.png
.. | [ Plus icon ] | image:: images/Add_icon.png
.. |image7| image:: images/exportnodetypes.png
.. |image8| image:: images/importnodetype.png
.. |image9| image:: images/Delete_icon.png
