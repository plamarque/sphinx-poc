Document templates
==================

In Templates, select Documents to open the Documents panel.

|image0|

The Documents templates are categorized into 3 sub-tabs that makes ease
for management. You can use default templates provided by PRODUCT in
each sub-type or define a new template.

-  The Documents tab includes **Contact Us**, **Product**, **Accessible
   Media**, **Announcement**, **CSS File**, **HTML File**, **Javascript
   File**, **Web Link**, **Illustrated Web Content**, **Web Content**,
   **File**, **Accessible Breadcrumb**, **Accessible Navigation**, and
   **Accessible Site Search Box**.

-  The Actions tab includes **Add Metadata Action**, **Automatic
   Versioning**, **Enable Versioning**, **Populate to Menu**, and **Add
   Category Action**.

-  The Others tab includes **Comments**, **Votes**, and **File
   Content**.

    **Note**

    -  **Contact Us** and **Product** are for the ACME site, so these
       templates only appear when the ACME site is enabled.

    -  **Accessible Breadcrumb**, **Accessible Navigation** and
       **Accessible Site Search Box** are for the WAI site, so these
       templates only appear when the WAI site is enabled.

    -  **Populate to Menu** only appears in the list of Action templates
       when the ACME site is enabled.

Editing/Deleting a Document template
------------------------------------

**Editing a Document template**

Select the template type tab (Documents, Actions or Others).

Click |image1| corresponding to your desired template in the Action
column.

The View & Edit Template form appears.

|image2|

Make changes on the values of each tab, including:

-  In the Template tab, you can edit the label of the template. The is
   Document Template checkbox is selected by default when you select the
   Documents tab. However, this checkbox is disabled by default when you
   select the Actions or Others tab.

-  In the Dialog tab, you can add a dialog, edit or delete an existing
   dialog. Besides, you can set permission to use the dialog form for a
   specific group and membership. Setting the \* membership will allow
   all users of the group to have this permission. For more details, see
   `Dialogs <../../../reference/html/PLFRefGuide.PLFDevelopment.TemplateConfiguration.Content.ContentTypes.Dialogs.html>`__.

-  In the View tab, you can add a view, edit or delete an existing view.
   Besides, you can set permission to view the template for a specific
   group and membership. Setting the \* membership will allow all users
   of the group to have this permission. For more details, see
   `Views <../../../reference/html/PLFRefGuide.PLFDevelopment.TemplateConfiguration.Content.ContentTypes.View.html>`__.

-  In the CSS tab, you can add a new stylesheet, edit or delete an
   existing stylesheet.

    **Note**

    -  You cannot delete the default dialog/view.

    -  You cannot change the dialog/view/CSS name.

    -  If you click Enable Versioning or Versioning activated checkbox,
       the edited dialog/view/CSS automatically increments one version
       after you have clicked **Save**. It is displayed at the Version
       column.

    -  After the dialog/view/CSS has been enabled versioning, you will
       see the Versions field and the Restore button at the bottom of
       the form. You can use Restore to roll back to a selected version.

**Deleting a Document template**

Simply click |image3| corresponding to the template you want to remove,
then select **OK** in the confirmation message.

Adding a new document template
------------------------------

Select the template type tab (Documents, Actions or Others).

Click Add Template at the bottom to open the Template Form window.

|image4|

    **Note**

    The is Document Template checkbox is selected by default when you
    select the Documents tab. However, this checkbox is disabled by
    default when you select the Actions or Others tab.

Select the template type from the Name drop-down menu.

Specify a name for the template in the Label field.

Click |image5| next to the Permission field to open the Select
Permission dialog.

Optionally, select the Dialog tab, View, and/or CSS and enter the value
in the input-text box.

Click Save to create the template.

.. |image0| image:: images/ecms/documents_template_panel.png
.. |image1| image:: images/common/edit_icon.png
.. |image2| image:: images/ecms/view_edit_template_form.png
.. |image3| image:: images/common/delete_icon.png
.. |image4| image:: images/ecms/add_new_template.png
.. |image5| image:: images/common/plus_icon.png
