Contributing content
====================

This function allows web-contributors to edit content, quickly access
content list folders from the homepage of the current site, publish
content without using the `Manage Publication <#ManagingPublication>`__
function in **Sites Explorer**.

This section consists of the following topics:

-  **`Edit
   mode <#PLFUserGuide.ManagingYourWebsites.ContributingContent.EditMode>`__**

   Introduction to the Edit mode in PRODUCT, how to enable and use this
   mode.

-  **`CKEditor <#PLFUserGuide.ManagingYourWebsites.ContributingContent.CKEditor>`__**

   Introduction to the additional features of CKEditor in PRODUCT.

Edit mode
---------

When you access the `Agital <#eXoAddonsGuide.WCM.Agital>`__ site, by
default, the site content is in the **published mode** and you cannot
edit them.

However, PRODUCT provides you with the **Edit** mode which enables you
to edit all content of the Agital site by using the `InContext
Editing <#PLFUserGuide.ManagingYourWebsites.ContributingContent.InContextEditing>`__
and `Inline
Editing <#PLFUserGuide.ManagingYourWebsites.ContributingContent-Inline_Editing>`__
features.

When hovering your cursor over content, you can see |image0| which
enables you to quickly edit this content in Sites Explorer. You can take
advantage of this feature to submit content to a page.

To turn on the **Edit** mode, click Edit on the top navigation bar, then
select Content from the drop-down menu.

For single content viewer (SCV), you can see the current state of the
content, the Edit Content icon and Preferences icon.

|image1|

For content list viewer (CLV), you can see the current state of the
content, the Edit Content icon, the Preferences icon, the Add Content
icon and the Manage Content icon.

|image2|

InContext Editing
~~~~~~~~~~~~~~~~~

By using the **InContext Editing** feature, the process of editing a
page becomes more intuitive. This feature allows you to edit content "in
context" without using the WYSIWYG editor, and the new content will
automatically override the old one.

To use **InContext Editing**, you first need to turn on the `Edit
Mode <#TurningOnTheEditMode>`__.

Adding content
^^^^^^^^^^^^^^

    **Note**

    Adding new content by using **InContext Editing** is enabled for the
    **content list viewer** (CLV) only.

Turn on the `Edit Mode <#TurningOnTheEditMode>`__, then hover your
cursor over the CLV to which you want to add new content.

Click |image3| on the CLV.

You will be redirected to the **Sites Explorer** in the creation form of
the content having the same type as other contents in the CLV.

|image4|

**Details:**

+-----------------------+----------------------------------------------------+
| Field                 | Description                                        |
+=======================+====================================================+
|                       | Maximizes/minimizes the screen.                    |
+-----------------------+----------------------------------------------------+
| Close                 | Closes the content creation form without saving    |
|                       | the content.                                       |
+-----------------------+----------------------------------------------------+
| Save and Close        | Saves the changes done and closes the creation     |
|                       | form.                                              |
+-----------------------+----------------------------------------------------+
| Save                  | Saves the changes done without closing the         |
|                       | creation form.                                     |
+-----------------------+----------------------------------------------------+

Fill all the fields in the form. The field name is required.

Click Save or Save & Close to save the content.

After closing the content form, you can view the content and do some
actions listed on the Action bar for the content. See the `Working with
basic actions <#PLFUserGuide.ManageDocuments.BasicActions>`__ for more
details.

|image5|

    **Note**

    The folder, where a document is saved, is the path you have selected
    in the `Managing
    preferences <#PLFUserGuide.ManagingYourWebsites.ContributingContent.InContextEditing.ManagingPreferences>`__
    section.

Editing content
^^^^^^^^^^^^^^^

You can edit any content on the homepage for SCV and CLV with
**InContext Editing**.

Turn on the `Edit Mode <#TurningOnTheEditMode>`__, then hover your
cursor over the content you want to edit, and click | pencil | at the
right corner. You will be directed to **Sites Explorer** with the
document form for you to edit.

|image7|

Make changes on the content, then click Save or Save & Close to accept
your changes.

After closing the Edit form, the content is in the Document View.

|image8|

Click |image9| to return to the site. In the **Edit** mode, your new
content will be in the "Draft" state with its visible modifications.

|image10|

Click |image11| to publish your edited content. Your content is now in
the "Published" state.

    **Note**

    You cannot see the edited content in the draft state when you turn
    off the **Edit** mode.

Managing content
^^^^^^^^^^^^^^^^

With **InContext Editing**, you can easily manage a content list viewer
on the page. You can add new content, edit, delete an existing content
or copy/cut/paste in the CLV and take more actions in the right-click
menu.

**Adding content in the CLV**

Turn on the `Edit Mode <#TurningOnTheEditMode>`__.

Hover your cursor over the CLV to which you want to add new content on
the homepage, and click |image12|.

You will be directed to the **Sites Explorer** page.

|image13|

Select | [ Add Document ] | on the Action bar.

Do the same steps as in the `Adding
Content <#PLFUserGuide.ManagingYourWebsites.ContributingContent.InContextEditing.AddingContent>`__
section.

**Do other actions**

You can do many different actions for specific content in the CLV. See
the `Working with basic
actions <#PLFUserGuide.ManagingYourDocuments.WorkingWithBasicActions>`__
section.

Managing preferences
^^^^^^^^^^^^^^^^^^^^

Preferences enable you to edit content in the single content viewer
(SCV) and the content list viewer (CLV), reset the display of the
content in SCV and CLV and publish content.

**Editing the single content viewer**

Turn on the `Edit Mode <#TurningOnTheEditMode>`__.

Hover your cursor over a single content viewer and select |image15| of a
single content viewer.

The Content Detail Preferences dialog appears.

|image16|

**Details:**

+-----------------------+----------------------------------------------------+
| Field                 | Description                                        |
+=======================+====================================================+
| The Content Selection | Content Path: Select the path of the content that  |
| tab                   | you want to show.                                  |
+-----------------------+----------------------------------------------------+
| The Display Settings  | Configure the visibility of Title, Date and Option |
| tab                   | Bar.                                               |
|                       |                                                    |
|                       | -  Show Title: Select this checkbox to display the |
|                       |    title of the content.                           |
|                       |                                                    |
|                       | -  Show Date: Select this checkbox to display the  |
|                       |    date of the content publication.                |
|                       |                                                    |
|                       | -  Show Option Bar: Select this checkbox to        |
|                       |    display the Option bar which is used to show    |
|                       |    the print link.                                 |
|                       |                                                    |
                                                                            
+-----------------------+----------------------------------------------------+
| The Print Settings    | -  Show in Page: The content is shown in the page. |
| tab                   |                                                    |
|                       | -  with: Parameters contain the content path.      |
|                       |                                                    |
                                                                            
+-----------------------+----------------------------------------------------+
| The Advanced tab      | This tab consists of two parts:                    |
|                       |                                                    |
|                       | -  Dynamic Navigation: Allow you to get a          |
|                       |    parameter to configure the portlet by URL. It   |
|                       |    means that the URL containing the content path  |
|                       |    can be dynamically changed.                     |
|                       |                                                    |
|                       |    -  Disable: The single content will be opened   |
|                       |       by an URL containing the Content Path.       |
|                       |                                                    |
|                       |    -  Enable: This portlet is configured with the  |
|                       |       provided parameter ("content-id" by default) |
|                       |       and the content.                             |
|                       |                                                    |
|                       | -  Content Visibility: Allow you to use a cache    |
|                       |    shared between users to get content. If you     |
|                       |    want to get content, which are displayed in CLV |
|                       |    or SCV, from one cache, select Restricted by    |
|                       |    Authentication. If not, select Restricted by    |
|                       |    User Roles. In most cases, you should not       |
|                       |    switch to Restricted by User Roles as it        |
|                       |    reduces the overall performance.                |
|                       |                                                    |
                                                                            
+-----------------------+----------------------------------------------------+

    **Note**

    Hover your cursor over | question mark | to see a quick help for
    each section.

Click |image18| next to the Content Path to select another content. The
Select Content dialog appears.

Select a folder in the left pane, and its content in the right pane. The
selected content will be displayed in the Content Path field.

Tick the checkboxes, including Show Title, Show Date and Show Option
Bar, if you want to display the content title, the publication date and
the print button like the illustration below.

|image19|

**i.** In the Print Setting part, click | magnifying glass | to open the
UIPageSelector dialog.

**ii.** Click | magnifying glass |, then click a folder on the left and
select a page which will show the content on the right by clicking
|image22|.

Click Save to save all your changes.

**Editing the content list viewer**

Turn on the `Edit Mode <#TurningOnTheEditMode>`__, then hover your
cursor over a content list viewer and select |image23|.

|image24|

The Content List Preferences dialog appears.

|image25|

**Details:**

+--------------------------+--------------------------------------------------+
| Field                    | Description                                      |
+==========================+==================================================+
| The Content Selection    | Mode: This mode is to select web content for the |
| tab                      | list viewer. There are two modes:                |
|                          |                                                  |
|                          | -  By Folder: Allows selecting a content folder  |
|                          |    in the Folder Path field.                     |
|                          |                                                  |
|                          | -  By Content: Allows selecting by the content   |
|                          |    in a specific folder in Folder Path field.    |
|                          |                                                  |
|                          | Folder Path: The path to a location of a folder  |
|                          | that contains the content.                       |
|                          |                                                  |
|                          | Order by: Sorts content in the List Viewer by    |
|                          | Title, Created Date, Modified Date, Published    |
|                          | Date, Event Date, or Index in the ascending or   |
|                          | descending order.                                |
+--------------------------+--------------------------------------------------+
| The Display Settings tab | Header: The title of all content that is shown   |
|                          | on the top of the content list viewer.           |
|                          |                                                  |
|                          | -  Automatic Detection: Ticks this checkbox to   |
|                          |    enable automatically detecting the header of  |
|                          |    the content list viewer basing on the current |
|                          |    selection.                                    |
|                          |                                                  |
|                          | Template: The template which is used to view the |
|                          | content list.                                    |
|                          |                                                  |
|                          | Paginator: The template which is used to view    |
|                          | each content in the list.                        |
|                          |                                                  |
|                          | Items per Page: The number of items which will   |
|                          | be displayed per page.                           |
|                          |                                                  |
|                          | The following options which can be shown or      |
|                          | hidden by ticking or unticking checkboxes        |
|                          | respectively.                                    |
|                          |                                                  |
|                          | -  Show Title: Title of each published web       |
|                          |    content/document.                             |
|                          |                                                  |
|                          | -  Show Header: Header of each published web     |
|                          |    content/document.                             |
|                          |                                                  |
|                          | -  Show Refresh: The Refresh button at the left  |
|                          |    bottom of the page.                           |
|                          |                                                  |
|                          | -  Show Image: The illustration of each          |
|                          |    published web content/document.               |
|                          |                                                  |
|                          | -  Show Date: The created date of each published |
|                          |    web content/document.                         |
|                          |                                                  |
|                          | -  Show More Links: The Read more link to read   |
|                          |    all the content of web content and/or         |
|                          |    document.                                     |
|                          |                                                  |
|                          | -  Show Summary: The summary of each web         |
|                          |    content/document.                             |
|                          |                                                  |
|                          | -  Show Link: The link of web content/document.  |
|                          |                                                  |
|                          | -  Show RSS Link: The RSS link of all content of |
|                          |    web content/document.                         |
|                          |                                                  |
                                                                             
+--------------------------+--------------------------------------------------+
| The Advanced tab         | Dynamic Navigation                               |
|                          |                                                  |
|                          | -  Disable: The single content will be opened by |
|                          |    an URL containing the Content Path.           |
|                          |                                                  |
|                          | -  Enable: This portlet is configured with the   |
|                          |    provided parameter (content-id by default).   |
|                          |                                                  |
|                          | -  By: This parameter is the key in the URL to   |
|                          |    let CLV know which really is the path in the  |
|                          |    current URL.                                  |
|                          |                                                  |
|                          | -  Show in Page: The single content in CLV will  |
|                          |    be shown in a selected page. You can select   |
|                          |    any page but should take one with a Content   |
|                          |    Detail Portlet. The "Dynamic Navigation" is   |
|                          |    enabled in the Content Detail Portlet that    |
|                          |    interprets the URL and shows a single         |
|                          |    content.                                      |
|                          |                                                  |
|                          | -  With: This parameter is the key in the URL to |
|                          |    let SCV know which really is the path in the  |
|                          |    current URL.                                  |
|                          |                                                  |
|                          | Content Visibility: Allows using a cache shared  |
|                          | between users to get content. If you want to get |
|                          | content which is displayed in CLV or SCV from    |
|                          | one cache, select Restricted by Authentication   |
|                          | (default). If not, select Restricted by User     |
|                          | Roles. In most cases, you should not switch to   |
|                          | Restricted by User Roles as it reduces the       |
|                          | overall performance.                             |
+--------------------------+--------------------------------------------------+

Select the Content Selection tab:

-  Select content you want to show on the content list viewer by
   clicking |image26| next to the Folder Path field.

   -  If you select the By Folder mode, select an available site on the
      left, then select a folder that contains content (documents and/or
      web content) on the right by clicking the folder.

   -  If you select the By Content mode, select an available folder from
      the left pane, all content in this folder will be listed in the
      right pane. Click content on the right that you want to add to the
      content list. There will be a message, informing that you have
      successfully added it to the Content List. The selected content
      will be listed in the Content List.

-  Click the Order by field and select one criterion to sort the content
   list in the ascending or descending order.

Select the Display settings tab:

-  Enter a header for the content list in the Header field if you want.

-  Select a template to display the content list in the template list.

-  Tick/Untick your desired options.

Select the Advanced tab to activate the dynamic navigation and select
the content visibility.

Click Save to accept your changes.

Inline Editing
~~~~~~~~~~~~~~

The **Inline Editing** mode allows you to edit directly on the page
without going to a separate one. By using this mode, you can edit the
text in the same location in such an intuitive and convenient manner.

**Do the Inline Editing**

Turn on the `Edit Mode <#TurningOnTheEditMode>`__, then hover your
cursor over the area you want to edit. The editable area will be
highlighted.

Click the area you want to edit.

|image27|

The Edit area will be displayed with the
`CKEditor <http://ckeditor.com/demo>`__ as below. (See more information
about CKEditor
`here <#PLFUserGuide.ManagingYourWebsites.ContributingContent.CKEditor>`__.)

|image28|

Make changes on your selected area.

Click |image29| to accept, or |image30| to discard changes.

-  After you have made changes on your content, it is in the **Draft**
   state.

-  Click |image31| to publish the content. Now, your edited content is
   in the **Published** state.

CKEditor
--------

When using CKEditor to write/edit a document in PRODUCT, you can also:

-  `Insert a site link to the
   document. <#PLFUserGuide.ManagingYourWebsites.ContributingContent.CKEditor.InsertingSiteLink>`__

-  `Insert a content link to the
   document. <#PLFUserGuide.ManagingYourWebsites.ContributingContent.CKEditor.InsertingContentLink>`__

-  `Upload an image to the
   document. <#PLFUserGuide.ManagingYourWebsites.ContributingContent.CKEditor.InsertingImage>`__

**Inserting a site link**

Click |image32| to open the Insert link to a site page form.

|image33|

Enter the site title of the link in the Title field.

Enter the site URL manually, or you can also click Get portal link to
open a page containing all the sites in the same server, then select one
that you want.

Click Preview to view the site.

Click Save to accept inserting the site to the document.

**Inserting a content link**

Click |image34| to open a page.

|image35|

Click the plus before the document name, or click directly the document
name in the left pane to show the content in the right pane, or click
|image36| to upload a file from your local device.

Click content that you want to insert to the document.

**Image Upload through CKEditor**

Click |image37| to open the upload image form.

|image38|

Click on Browse server to open the WCM Content selector allowing to
upload from desktop or to select an existing attached image.

-  By default, the WCM content selector opens the folder where the
   webcontent/Illustrated webcontent will be saved.

   |image39|

   In this case, the webcontent is added under
   ``sites/intranet/web contents``.

-  If the WCM Content selector has already been opened and a file has
   been selected then this last location will be displayed.

   |image40|

   As an example of this case:

   -  Go to file Explorer under /sites/intranet/web contents and create
      a new webcontent.

   -  Click |image41| to insert an image and then Browse server.

   -  The WCM content selector opens the folder
      ``/sites/intranet/web contents`` (the first case). Browse to get,
      for example, under the path ``sites/intranet/medias``, upload an
      image and insert it to the webcontent.

   -  Reclick |image42| and then on Browse server, the WCM contents
      selector will open the last location which is
      ``sites/intranet/medias`` and not the default one
      ``/sites/intranet/web contents``.

Select an image from the existing ones or click on |image43| to upload
an image from your desktop then select it.

The image will be first previewed in the Image properties form.

|image44|

Click OK, the image will be inserted in the webcontent.

To finalize the webcontent/illustrated webcontent creation, click on
Save or Save and close.

|image45|

.. |image0| image:: images/common/edit_portlet_icon.png
.. |image1| image:: images/ecms/single_content_viewer.png
.. |image2| image:: images/ecms/content_list_viewer.png
.. |image3| image:: images/ecms/add_content_icon1.png
.. |image4| image:: images/ecms/content_forms.png
.. |image5| image:: images/ecms/new_content.png
.. | pencil | image:: images/common/edit_portlet_icon.png
.. |image7| image:: images/ecms/edit_form_in_sites_explorer.png
.. |image8| image:: images/ecms/edited_content_in_document_view.png
.. |image9| image:: images/ecms/back_icon.png
.. |image10| image:: images/ecms/draft_content.png
.. |image11| image:: images/ecms/publish-icon1.png
.. |image12| image:: images/ecms/manage_content_icon.png
.. |image13| image:: images/ecms/add_new_content_to_CLV.png
.. | [ Add Document ] | image:: images/ecms/new_content_button.png
.. |image15| image:: images/common/preferences_icon.png
.. |image16| image:: images/ecms/content_detail_preferences.png
.. | question mark | image:: images/common/tooltip_icon.png
.. |image18| image:: images/common/plus_icon.png
.. |image19| image:: images/ecms/scv_show_options.png
.. | magnifying glass | image:: images/common/search_icon.png
.. | magnifying glass | image:: images/common/up_arrow_icon.png
.. |image22| image:: images/common/select_green_icon.png
.. |image23| image:: images/common/preferences_icon.png
.. |image24| image:: images/ecms/clv_preferences.png
.. |image25| image:: images/ecms/content_list_preferences.png
.. |image26| image:: images/common/plus_icon.png
.. |image27| image:: images/ecms/inline_editing_form.png
.. |image28| image:: images/ecms/CKEditor_Inline.png
.. |image29| image:: images/common/accept_icon.png
.. |image30| image:: images/common/cancel_icon.png
.. |image31| image:: images/ecms/publish-icon1.png
.. |image32| image:: images/ecms/insert_portal_link.png
.. |image33| image:: images/ecms/insert_link_to_a_site_page.png
.. |image34| image:: images/ecms/insert_content.png
.. |image35| image:: images/ecms/content_selector_form.png
.. |image36| image:: images/platform/upload_button.png
.. |image37| image:: images/ecms/UploadImageCKEditor_button.png
.. |image38| image:: images/ecms/imageProperties.png
.. |image39| image:: images/ecms/rootlocation.png
.. |image40| image:: images/ecms/mediafolder.png
.. |image41| image:: images/ecms/UploadImageCKEditor_button.png
.. |image42| image:: images/ecms/UploadImageCKEditor_button.png
.. |image43| image:: images/ecms/upload.png
.. |image44| image:: images/ecms/preview.png
.. |image45| image:: images/ecms/save.png
