Importing
=========

Content which is in the ``.xml`` file format can be imported into the
JCR Explorer system.

Select the location where you want to import the new content.

Click |image0| on the Action bar to open the Import form.

|image1|

Select the file in the Upload File field and navigate to the file you
want to import.

Select one value from the UUID Behaviour drop-down menu. In case there
is UUID conflict - the situation when an imported node has the same UUID
as an existing node, the behavior will be applied for those two nodes,
as follows:

Create New
    New UUID will be generated and assigned to the imported node. There
    is no impact to the existing one.

Remove Existing
    The already existing node (and its subtree) is removed from wherever
    it may be in the workspace before the incoming node is added.

Replace Existing
    The already existing node is replaced by the incoming node in the
    same path as the existing node. This behavior may result in the
    incoming subtree being disaggregated to different locations in the
    workspace.

Throw Exception
    The node is not imported. No impact to the existing one.

Select the file for the Version History field.

Click Import to import the file's selected version.

.. |image0| image:: images/common/import_button.png
.. |image1| image:: images/ecms/import_form.png
