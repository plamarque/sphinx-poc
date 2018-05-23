Sharing via Activity Composer
=============================

PRODUCT continuously improves the pleasure and value in engaging with
the users' community by integrating the **Auto-share** feature into the
Documents application. This integration fundamentally complies with
privacy rules; that is what made in folders (except Public) of the
Personal Documents drive will not be shared on Activity Stream.
Therefore, **Auto-share** is only featured in spaces, and you are
required to be owner or member of the space to see activities updated in
the space's Activity Stream. At the same time, these activities are also
updated in the **Social Intranet** homepage.

Assume that you have created a space or are a member of a space named
**PRODUCT TEAM**, then start doing certain actions in the **Documents**
application of this space.

|image0|

Many of the actions (for example, uploading, editing or sharing a
document) will be automatically shared on **Activity Stream** although
you do not take direct actions to share them. As a result, another
members can see what you are doing on your content via **Activity
Stream**.

Creating a new activity
-----------------------

Once you have finished uploading or sharing a file to the **Documents**
application of the **PRODUCT TEAM** space, one new activity will be
created on **Activity Stream**.

|image1|

Here, you can see the following main information of the uploaded file:

-  The file name |image2| or title |image3|, if any.

-  The file description |image4|, if any.

-  The file version |image5| and size |image6|, if any.

    **Note**

    -  If the uploaded file is an image, the preview image will be
       displayed on the activity content as a filetype icon.

    -  If the uploaded file is of PDF or Office, the preview image will
       be its first page.

    -  If the activity is a document sharing action, a label "*shared a
       document*\ " will be attached to the activity content.

From **Activity Stream**, you can:

-  Click |image7| to view the document in a larger window.

-  Click |image8| to download the document.

-  Click |image9| to go directly into the **Documents** application and
   edit this document.

-  Click |image10| to give your idea.

-  Click |image11| to show your liking to the uploaded document.

Share multiple documents in activity stream
-------------------------------------------

With PRODUCT, it is possible to share activities with multiple
documents. In addition, the upload pop up is improved in order to make
easier and ergonomic the upload process.

**Share multiple files in the activity stream**

To publish an activity with multiple documents, follow these steps:

In the microblog, select File tab. The activity composer will suggest
you either to drop files from your computer using the mouse, to upload
manually from desktop or mobile or to select from existing uploads in
PRODUCT.

|image12|

-  Drag and Drop: Allows you to drag and drop files from your hard disc.

   |image13|

   When droping the file, the area dedicated to the files upload is
   greyed.

-  upload manually: Allows you to select documents from your hard disc.

   |image14|

   Cliking on upload manually opens a window showing a drive from your
   hard disk (it opens files drive for mobile devices) and allows you to
   select one or many files.

-  select from existing uploads: Allows you to select documents from
   your PRODUCT drives.

   |image15|

   You can select documents from Personal Documents drive, it is opened
   by default when clicking on select from existing uploads, or you can
   change to any drive you want.

   If the activity is in a space, the select from existing uploads
   action will open by default the space's drive. It is also possible to
   change the drive.

   |image16|

    **Note**

    When you choose to upload manually or drag and drop files to the
    activity composer, these files will be added to the the folder
    ``/Public/Activity Stream Documents`` under the Personal Documents
    drive.

    If the activity is posted in a space's activity stream, the files
    will be added to the folder ``/Activity Stream Documents`` under the
    space's drive.

Choose the manner with which you will upload your files then select one
or more files.

An information box appears under the activity composer, it indicates
information about the file upload progress and displays the file size.

    **Note**

    By default, it is allowed to attach up to 20 files per activity and
    each file's size should not exceed 200 MB. These parameters are
    configurable in
    `exo.properties <#PLFAdminGuide.Configuration.ConfigurationOverview>`__
    file. More details
    `here <#PLFAdminGuide.Configuration.CustomizeMultiupload>`__.

|image17|

You can cancel the upload of a file by clicking on |image18| or remove a
fully uploaded file by clicking on |image19|.

Click on Post to publish documents in the activity stream.

    **Note**

    -  When a user posts an activity in an another user's profile, this
       user receives an email notification.

    -  When a user posts an activity in a space, all the space members
       will receive an email notification.

    This email notification will contain all the shared files on a list
    with the file icon type, the file name and the file size. Clicking
    on a file name in the email notifications opens it in the Documents
    application.

**Multiple files preview in the activity stream**

While published, an activity appears displaying the attached files
ordred by selection order on the files list.

|image20|

Up to three files are previewed in the activity and a link containing
the number of the other files. Clicking on it opens the following file
from the list of uploaded files.

-  When the user uploads only one file, the file’s container will take
   100% of the file activity area.

-  When two files are displyed in the activity, the file’s container
   splitting will be 50% for File1 and 50% for File2.

-  When three files are added in an activity post, the file’s container
   splitting will be 50% for File1, 25% for File2 and 25% for File3.

-  When the user displays more than three files, the file’s container
   splitting will be 50% for File 1, 25% for File2 and 25% to display
   (+X-2 more) link where X is the total number of files added.

    **Note**

    If the file uploaded has a preview (such as pdf, images, docx...), a
    part of it is displayed. If the file has not a preview (such as
    html, zip, war..), a thumbnail of its extension is dispalyed and a
    breadcrumb containing infomation about it.

    |image21|

When the user hovers over the file's container, information about the
attached file is displayed. We will have:

|image22|

-  The filename.

-  The file's version (if it is different from the initial version).

-  The file location as a breadcrumb (each element is clickable).

-  The last update timestamp (including the creation date).

-  The last user who made the latest update.

-  The file size.

Each segment of the breadcrumb is clickable and clicking on one of them
opens the documents application in the corresponding location:

-  Clicking on the filename of the breadcrumb opens the file in
   Documents application.

-  Clicking on the file's version opens the version history of the file.

-  Clicking on a segment of the file's location opens the corresponding
   drive/folder.

-  Clicking on other details (update timestamp, User or size) opens the
   file's preview in activity stream.

For mobile devices, the breadcrumb also appears for shared files. When
any of the breadcrumb's details exceeds the screen size, it is either
preceeded or followed by an ellipsis.

The breadcrumb behaves same as for web, its segments are clickable and
it redirects to the correcsponding location as described above.

|image23|

    **Note**

    A Download all button appears under the activity allowing to
    download all the files of the activity. It will generate a zip file
    named **Activity\_ID\_Date**.

    Date can be in Frensh format if the user is using the Frensh
    language and in English format if the user is using English or any
    other language except Frensh.

You can navigate through the list of files by clicking on previous
|image24| and next |image25| buttons. For mobile devices, you should
scroll the screen left for next and right for previous. You can also
close the file preview by clicking on close button.

|image26|

Clicking on a file opens it to be previewed similar as `Document
viewer <#PLFUserGuide.ManagingYourDocuments.DocumentViewer>`__.

The breadcrumb appears also in the file's preview but only the file's
location is clickable.

    **Note**

    When an activity contains some files with permissions (i.e a UserA
    is not allowed to view some or all documents in the activity),
    this/these file(s) will not be displayed in the activity stream of
    users who don't have the permission to view.

Deleting all files of an activity leads to the whole activity deletion
and deleting one or more files from the activity eliminates these files
from the display.

**Multiple file sharing conditions**

-  If you attach more than the allowed number of files, a warning
   appears indicating that you can attach only 20 files.

   |image27|

-  When selecting more than 20 files form existing uploads, a warning
   appears in the drive indicating that only 20 files are allowed to be
   attached.

   |image28|

-  If you attach a file or many files exceeding 200MB, a warning appears
   to remember you the maximum size allowed.

   |image29|

-  When trying to attach the same file twice, a warning appears to
   indicate you that the file is already attached.

   |image30|

-  If you have, in the same drive, two files having the same name and
   you try to attach both of them, a warning appears indicating that the
   file is already attached.

   |image31|

Updating activity for document changes
--------------------------------------

**Editing a document**

Once you have made the following changes in the **Edit** form, new
comments will be auto-generated on the document activity.

-  Adding/Removing a category |image32|

-  Changing the document's language |image33|

-  Adding/Removing the file source |image34|

-  Adding/Removing the document description |image35|

-  Adding/Removing the document title\ |image36|

-  Adding/Removing the document creator\ |image37|

For example:

|image38|

    **Note**

    For changes on the Content field, you need to pay attention to the
    followings:

    -  If you remove the document content, there will be no comment on
       the document activity. However, in case your document is of
       image, PDF, Office Document, the preview image will be
       disappeared from **Activity Stream**.

    -  If you upload a new content for this document, the activity
       content will be updated with a new comment.

**Updating Metadata**

Once you have made any changes on the document metadata, there will be a
new comment on the document activity. For example:

|image39|

**Renaming a document**

Once you have renamed a document, the new name will be updated on the
document activity with a new comment informing about that.

|image40|

**Checking in a document**

Checking in a document does not result in any new comment on the
document activity. However, a version number will be updated on the
document activity.

|image41|

**Adding/Removing a tag**

Once you have added or removed a tag from the document, there will be a
new comment on the activity for such changes.

|image42|

**Commenting on a document**

Once you have commented on a document, there will a new comment on the
document activity for such change.

|image43|

However, there will be no comment or no update on the document activity
if you edit or remove the comment from the document.

**Moving a document**

When you move a document to another folder, there will be a new comment
on the document activity for such change.

|image44|

**Deleting a document**

If you delete any document from the **Documents** application, all
activities related to this document on **Activity Stream** will be
deleted without any comment or notification.

.. |image0| image:: images/ecms/space_documents.png
.. |image1| image:: images/ecms/share_upload.png
.. |image2| image:: images/common/1.png
.. |image3| image:: images/common/2.png
.. |image4| image:: images/common/3.png
.. |image5| image:: images/common/4.png
.. |image6| image:: images/common/5.png
.. |image7| image:: images/common/eye_view_button.png
.. |image8| image:: images/common/download_button.png
.. |image9| image:: images/common/edit_button.png
.. |image10| image:: images/common/comment_icon.png
.. |image11| image:: images/common/like_icon.png
.. |image12| image:: images/ecms/MultiUpload_step1.png
.. |image13| image:: images/ecms/Multiupload_drop.png
.. |image14| image:: images/ecms/Multiupload_manualSelect.png
.. |image15| image:: images/ecms/Multiupload_driveSelect.png
.. |image16| image:: images/ecms/Multiupload_driveChange.png
.. |image17| image:: images/ecms/Multiupload_cancel-delete.png
.. |image18| image:: images/ecms/cancel.png
.. |image19| image:: images/ecms/delete.png
.. |image20| image:: images/ecms/Multiupload_display.png
.. |image21| image:: images/ecms/preview_no_preview.png
.. |image22| image:: images/ecms/Multiupload_mouse_hover.png
.. |image23| image:: images/ecms/Mobile_breadcrumb.png
.. |image24| image:: images/ecms/previous.png
.. |image25| image:: images/ecms/next.png
.. |image26| image:: images/ecms/previous_next.png
.. |image27| image:: images/ecms/Multiupload_Error2.png
.. |image28| image:: images/ecms/Multiupload_Error2_2.png
.. |image29| image:: images/ecms/Multiupload_Error.png
.. |image30| image:: images/ecms/Multiupload_Error3.png
.. |image31| image:: images/ecms/Multiupload_Error3_2.png
.. |image32| image:: images/common/1.png
.. |image33| image:: images/common/2.png
.. |image34| image:: images/common/3.png
.. |image35| image:: images/common/4.png
.. |image36| image:: images/common/5.png
.. |image37| image:: images/common/6.png
.. |image38| image:: images/ecms/share_document_changes.png
.. |image39| image:: images/ecms/share_updated_metadata.png
.. |image40| image:: images/ecms/comment_rename_document.png
.. |image41| image:: images/ecms/share_version_document.png
.. |image42| image:: images/ecms/share_add_remove_tag.png
.. |image43| image:: images/ecms/share_comment.png
.. |image44| image:: images/ecms/share_move_document.png
