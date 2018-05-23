Node types
==========

This function is used to control all node types in PRODUCT.

In Repository, select Node Types to open the Node Types panel.

|image0|

**Viewing node types**

Click |image1| corresponding to the node you want to view. The View Node
Type Information form will appear.

|image2|

Click Close at the bottom of the form to exit.

**Adding a node type**

Click Add at the bottom of the **Node Types** page to open the Add/Edit
Node Type Definitions form.

|image3|

Select a namespace for the node.

Enter a name in the Node Type Name field. This field is mandatory and
its value must be unique.

    **Note**

    The name must not contain special characters, such as
    !,#,$,&,\*,(,).

Select a value for the Is Mixin Type field.

-  True: This node is Mixin type.

-  False: This node is not Mixin type.

Select a value for the Orderable Child Nodes field.

-  True: Child nodes are ordered.

-  False: Child nodes are not ordered.

Enter a value for the Primary Item Name field.

Enter a value for the Super Types field. Clicking |image4| will direct
you to the Super Types tab for you to search for available super types.

-  Property Definitions: Lists all definition names of the Property tab.

-  Child Node Definitions: Lists all definition names of the Child Node
   tab.

Click Save to accept adding a new node type, or Save as Draft to save
this node type as draft.

**Importing node types**

Click Import at the bottom of the **Node Types** page to open the Import
Node Type From XML File form.

|image5|

Click Select File to upload a file.

    **Note**

    You must upload an XML or ZIP file. This file is in the node type's
    format.

Click the Upload button.

    **Note**

    If you want to upload another file, click |image6| to delete the
    file which has just been uploaded, then upload other files.

Tick the checkboxes corresponding to the nodes that you want to import.

Click Import to complete importing a node type.

**Exporting node types**

Click Export at the bottom of the **Node Types** page to open the Export
Node Types form.

|image7|

Click Uncheck all if you do not want to export all node types. After
clicking Uncheck all, this button becomes the Check all button.

Select nodes that you want to export by ticking the corresponding
checkboxes.

Click Export in this form.

Select the location in your device to save the exported node.

    **Note**

    You must select at least 1 node type to be exported. If you do not
    want to export the node, click Cancel to quit this pop-up.

.. |image0| image:: images/ecms/node_types_panel.png
.. |image1| image:: images/common/view_icon.png
.. |image2| image:: images/ecms/view_node_type_information_form.png
.. |image3| image:: images/ecms/add_edit_node_type_definitions.png
.. |image4| image:: images/common/search_icon.png
.. |image5| image:: images/ecms/import_nodetype.png
.. |image6| image:: images/common/delete_icon.png
.. |image7| image:: images/ecms/export_node_types.png
