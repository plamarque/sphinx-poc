Add a document
==============

    **Warning**

    TODO: give examples of types of documents + redo the Table + Check
    with Dev to remove: Create a new article, Create a new Podcast,
    Create a new Sample node, Create a new File Plan, Create a new Kofax
    document, Create a new event ? REMOVE from RELOOKING.

There are several types of document in PRODUCT, such as File, and more.

The table below shows types of nodes which can be added to various
document types. The rows indicate which nodes in the left column can be
added. The columns indicate which nodes at the top can contain.

+-----------------------+-------------+-------------+-------------+---------------+-------------+------------------+------------------+-------------------+
|                       | File        | Article     | Podcast     | Sample node   | File Plan   | Kofax document   | Content folder   | Document folder   |
+=======================+=============+=============+=============+===============+=============+==================+==================+===================+
| **File**              | |image57|   | |image58|   | |image59|   | |image60|     | |image61|   | |image62|        | |image63|        | |image64|         |
+-----------------------+-------------+-------------+-------------+---------------+-------------+------------------+------------------+-------------------+
| **Article**           | |image65|   |             | |image66|   |               |             | |image67|        | |image68|        |                   |
+-----------------------+-------------+-------------+-------------+---------------+-------------+------------------+------------------+-------------------+
| **Podcast**           | |image69|   | |image70|   | |image71|   | |image72|     | |image73|   | |image74|        | |image75|        | |image76|         |
+-----------------------+-------------+-------------+-------------+---------------+-------------+------------------+------------------+-------------------+
| **Sample node**       | |image77|   |             | |image78|   |               |             | |image79|        | |image80|        |                   |
+-----------------------+-------------+-------------+-------------+---------------+-------------+------------------+------------------+-------------------+
| **File Plan**         | |image81|   |             | |image82|   |               | |image83|   | |image84|        | |image85|        | |image86|         |
+-----------------------+-------------+-------------+-------------+---------------+-------------+------------------+------------------+-------------------+
| **Kofax**             | |image87|   | |image88|   | |image89|   | |image90|     | |image91|   | |image92|        | |image93|        |                   |
+-----------------------+-------------+-------------+-------------+---------------+-------------+------------------+------------------+-------------------+
| **Uploaded file**     | |image94|   | |image95|   | |image96|   | |image97|     | |image98|   | |image99|        | |image100|       | |image101|        |
+-----------------------+-------------+-------------+-------------+---------------+-------------+------------------+------------------+-------------------+
| **Content folder**    | |image102|  | |image103|  | |image104|  | |image105|    |             | |image106|       | |image107|       |                   |
+-----------------------+-------------+-------------+-------------+---------------+-------------+------------------+------------------+-------------------+
| **Document folder**   | |image108|  |             | |image109|  |               | |image110|  | |image111|       | |image112|       | |image113|        |
+-----------------------+-------------+-------------+-------------+---------------+-------------+------------------+------------------+-------------------+

    **Note**

    | green tick | indicates that the corresponding document can be
    added into. A blank entry means that the corresponding document
    cannot be added into.

    Following the horizontal, you will know which nodes can be added.

    Following the vertical, you will know which node can be included.

**Add a new document**

Select a folder from the left pane where you want to add a new document.

Click | [ Add Document ] | on the **Action** bar to open a list of
content templates.

|image116|

Click your desired template. See more details in `Step
3 <#proc-User_Guide-Add_Content-Add_a_new_content-step3>`__ of the `Add
content <#PLFUserGuide.ManagingYourWebsites.ContributingContent.InContextEditing.AddingContent>`__
section.

Each document (except Article) must be added to categories when being
created.

**Attach files to a document**

Select a document or a folder that you want to attach files, and click |
[ Upload ] | on the **Action** bar.

The Upload File form will appear.

|image118|

Enter a name into the Name field. If not, the Name field is
automatically filled with the file name.

Click Browse... to select the attachment file. You can click | plus | to
add more files.

Click Save to attach the files.

To view the attached file directly in **Sites Explorer**, simply click
its name.

|image120|

    **Note**

    PRODUCT enables you to view all types of documents, such as Open
    Office, Microsoft Office in the PDF format.

**Create a new File document**

Follow the steps in the `Add a new
document <#proc-User_Guide-Add_a_document-Add_a_new_document>`__ section
to open the corresponding form to add a File document.

Input a name for the file document in the Name field. Some special
characters (@ # % & \* ( ) " ' : ; [ ] {} / !) cannot be used in the
Name field.

Click the Mime Type field and select one type. There are three types of
File document:

-  text/html: when creating a text/html File document, you can input
   values like source code (HyperText Markup Language HTML) in the
   **Content** field . After being created, it will generate the content
   you want, then you can see both the input source code and the
   generated content in that document.

-  text/plain: after a text/plain File document is created, it will
   display exactly what you input in the Content field.

-  application/x-groovy+html: it indicates your file as a groovy file.

Input a value in the **Content** field:

-  text/html or application/x-groovy+html: if you want to create a File
   document with a source code and generated content, click the | [
   Source ] | button in the **Editor** bar.

-  text/plain: if you select text/plain type, the content field will be
   displayed like the following illustration.

   |image122|

Optionally, fill values in all the rest fields, including Title,
Description, Creator and Source.

Click | plus | to open more fields.

Click Save or Save & Close to accept creating a new file document.

After being created successfully, a file document with the text/html
type will be displayed like the illustration below.

|image123|

|image124|

**Create a new article**

Follow the steps in the `Add a new
document <#proc-User_Guide-Add_a_document-Add_a_new_document>`__ section
to open the corresponding form to add a new Article document.

Input name and title of the Article in the Name and Title fields.
Special characters (@ # % & \* ( ) " ' : ; [ ] {} / !) are not allowed
in the Name field.

Input values for both fields: Summary and Content.

Click Save or Save & Close to accept the inputted values.

After being created, your newly added Article document will be shown as
below.

|image125|

The Links area lists all its related documents. After adding relations
to a document, Article will be displayed. You can click these links to
view the content of the related documents. For more details about how to
add a relation to a document, refer to the `Add a
relation <#sect-User_Guide-Manage_Relations-Add_a_relation>`__ section.

The Attachments area lists all its uploaded files/documents which are
attached with the Article. You can remove the attachments by clicking |
trash can |.

For more details about how to add an attachment, see the `Attach files
to a
document <#proc-User_Guide-Add_a_document-Attach_files_to_a_document>`__
section.

    **Note**

    The name of document may be as the same to that of the existing one.
    When a new document is created with the same name as other existing
    document, a numeric index will be added to the name (for example,
    test [2]).

**Create a new Podcast**

Follow the steps in the `Add a new
document <#proc-User_Guide-Add_a_document-Add_a_new_document>`__ section
to open the corresponding Podcast form.

|image127|

**Details:**

+----------------+----------------------------------------------------------------------------------------------------------------------------------+
| Field          | Description                                                                                                                      |
+================+==================================================================================================================================+
| Name           | The document name which is required. Special characters (@ # % & \* ( ) " ' : ; [ ] {} / !) are not allowed in the Name field.   |
+----------------+----------------------------------------------------------------------------------------------------------------------------------+
| Categories     | Categories of a document.                                                                                                        |
+----------------+----------------------------------------------------------------------------------------------------------------------------------+
| Title          | The display name of a document.                                                                                                  |
+----------------+----------------------------------------------------------------------------------------------------------------------------------+
| Link           | The link to the source path of the uploaded media file that is required.                                                         |
+----------------+----------------------------------------------------------------------------------------------------------------------------------+
| Author         | The author of the uploaded media file.                                                                                           |
+----------------+----------------------------------------------------------------------------------------------------------------------------------+
| Explicit       | It is used to indicate if your Podcast episodes contain an explicit content or not.                                              |
+----------------+----------------------------------------------------------------------------------------------------------------------------------+
| Category       | The category of the uploaded media file, for example music, film, or short clip.                                                 |
+----------------+----------------------------------------------------------------------------------------------------------------------------------+
| Keyword        | This field allows you to search your Podcast files more quickly. You can use commas to separate between keywords.                |
+----------------+----------------------------------------------------------------------------------------------------------------------------------+
| Publish Date   | The date when an episode was released.                                                                                           |
+----------------+----------------------------------------------------------------------------------------------------------------------------------+
| Description    | Information about the uploaded media file.                                                                                       |
+----------------+----------------------------------------------------------------------------------------------------------------------------------+
| Mime Type      | The type of the uploaded media file.                                                                                             |
+----------------+----------------------------------------------------------------------------------------------------------------------------------+
| Length         | The length of the uploaded media file.                                                                                           |
+----------------+----------------------------------------------------------------------------------------------------------------------------------+

Input values for fields. To upload a media file, click Browse... and
select the media file from your device.

Click Save or Save & Close to finish.

Once being created, a Podcast will be displayed.

|image128|

**Create a new Sample node**

Follow the steps in the `Add a new
document <#proc-User_Guide-Add_a_document-Add_a_new_document>`__ section
to open the **Sample node** form.

Complete the appropriate fields.

Click Browse... to locate your desired image, and upload it.

Click Save or Save & Close to finish.

After being created, a new sample node will be displayed.

|image129|

The Relations area is used to list all its related documents. See the
`View a relation <#sect-User_Guide-Manage_Relations-View_Relations>`__
section.

You can click the links to view content of the related document.

The Attachments area is used to list all its uploaded files. See the
`Attach files to a
document <#proc-User_Guide-Add_a_document-Attach_files_to_a_document>`__
section for more details.

**Create a new File Plan**

Follow the instructions in the `Add a new
document <#proc-User_Guide-Add_a_document-Add_a_new_document>`__ section
to open the corresponding form to add a File Plan document.

**Details:**

-  The Name tab

   +------------------+------------------------------------------------------------------------------------------------+
   | Field            | Description                                                                                    |
   +==================+================================================================================================+
   | Name             | The name of the file plan.                                                                     |
   +------------------+------------------------------------------------------------------------------------------------+
   | Categories       | Categories of your file plan. Select the categories for your file plan by clicking | plus |.   |
   +------------------+------------------------------------------------------------------------------------------------+
   | Language         | The language of the File Plan document.                                                        |
   +------------------+------------------------------------------------------------------------------------------------+
   | File Plan Note   | Note for presenting any other information for users.                                           |
   +------------------+------------------------------------------------------------------------------------------------+

-  The Record Properties tab

   |image130|

   +------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | Field                              | Description                                                                                                                                                                                                                     |
   +====================================+=================================================================================================================================================================================================================================+
   | Record Category Identifier         | The alphanumeric identifier indicates a unique record category. This must be a unique ID. If this field is left blank, it will be created automatically by the system.                                                          |
   +------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | Disposition Authority              | A reference number to the regulations that govern the disposition.                                                                                                                                                              |
   +------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | **Permanent Record Indicator**     | A type of record indicators which should never be deleted.                                                                                                                                                                      |
   +------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | Disposition Instructions           | A readable guideline on how to handle the records associated with the file plan.                                                                                                                                                |
   +------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | Contains Records Folder            | The confirmation is about whether the records folder is contained or not.                                                                                                                                                       |
   +------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | Default Media Type                 | The choice for preset media types which are made available to simplify the data entry for the record. The frequently-chosen value is "electronic" or paper.                                                                     |
   +------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | Default Marking List               | Handling and classifying information that is printed at the bottom of the record, such as UNCLASSIFIED, or NOCONTRACT.                                                                                                          |
   +------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | Default Originating Organization   | This option is to enter the original arrangement as default which is made available to simplify the data entry for the record and to assume that originating organizations are the same for the information in the file plan.   |
   +------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | Vital Record Indicator             | This flag is to allow tracking or reminding you of the record as essential or not.                                                                                                                                              |
   +------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | Vital Record Review Period         | The choice for the interval of time between vital record reviews.                                                                                                                                                               |
   +------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

-  The Process Properties tab

   |image131|

   +-----------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | Field                       | Description                                                                                                                                                                                                                                               |
   +=============================+===========================================================================================================================================================================================================================================================+
   | Process Cutoffs             | The Boolean data type is used to break a process. If the process cutoff flag is set in the file plan, the record is cutoff after the expiration, or after it has been obsolete or superseded, depending on the information in the file plan.              |
   +-----------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | Event Trigger               | The text data type is an automatic executing code which is used to tell the event to perform some actions.                                                                                                                                                |
   +-----------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | Cutoff Period               | The duration for the record cutoff performance.                                                                                                                                                                                                           |
   +-----------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | Cutoff on Obsolete          | The record is cutoff when it is obsolete.                                                                                                                                                                                                                 |
   +-----------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | Cutoff on Superseded        | The record is cutoff when it is removed or replaced.                                                                                                                                                                                                      |
   +-----------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | Process Hold                | This boolean data type is used when a record process may be held before the further disposition is handled.                                                                                                                                               |
   +-----------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | Hold Period                 | The duration when a record may be held after cutoff which is normally measured in Years.                                                                                                                                                                  |
   +-----------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | Discretionary Hold          | The Boolean data type is used when a hold may be discretionary, such as after a command change. So, the discretionary hold flag allows the records management module to track these manual checks.                                                        |
   +-----------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | Process Transfer            | The boolean data type is used to determine how a record process will be transferred.                                                                                                                                                                      |
   +-----------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | Default Transfer Location   | The text data type is used to determine where a record is transferred by default.                                                                                                                                                                         |
   +-----------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | Transfer Block Size         | The float data type is used to determine in what size blocks for organizational purposes that is normally measured in Years.                                                                                                                              |
   +-----------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | Process Access              | The Boolean data type is flagged when a record, which is held permanently, must be ultimately transferred to the national records authority.                                                                                                              |
   +-----------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | Access Location             | The text data type is flagged to specify an area for the access transfer.                                                                                                                                                                                 |
   +-----------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | Access Block Size           | The text data type is flagged to determine the blocks size for organizational purposes which is normally measured in Years.                                                                                                                               |
   +-----------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | Process Destruction         | The Boolean data type is flagged if there is any record to be destroyed. After that, the record is marked in the Alfresco system to be permanently destroyed so that all information, metadata and physical traces are removed and cannot be recovered.   |
   +-----------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Fill in the appropriate fields of the tabs in the form.

Click Save or Save & Close to finish.

**Create a new Kofax document**

Follow the instructions in the `Add a new
document <#proc-User_Guide-Add_a_document-Add_a_new_document>`__ section
to open the Add Kofax Document form.

|image132|

Input a name for a Kofax document in the Name field which is required.
Special characters (@ # % & \* ( ) " ' : ; [ ] { } / !) are not allowed
in this field.

Select categories for a Kofax document by clicking | plus |.

Click Save or Save & Close to finish.

After being created, a Kofax document will be displayed.

-  The File View tab is used to display all added nodes in that Kofax.
   Besides, all added files in Kofax are also displayed in the Document
   View tab.

**Create a new event**

Follow the instructions in the `Add a new
document <#proc-User_Guide-Add_a_document-Add_a_new_document>`__ section
to open the Add an event document form.

Enter a title for the event.

Input the location where the event will take place in the Location
field. Select the Google Maps checkbox if you want the location of the
event to be shown on Google Maps.

Enter the Start and End Date/Time of the event.

Fill the Summary and Content fields.

Click Save or Save & Close to finish.

After being created, the event will be displayed like the illustration
bellow.

**Create an accessible media**

Follow the instructions in the `Add a new
document <#proc-User_Guide-Add_a_document-Add_a_new_document>`__ section
to open the content template list, and select the Accessible Media
template.

|image133|

**Details:**

+---------------------+---------------------------------------------------------------------------------------------------------------------------------------------------+
| Field               | Description                                                                                                                                       |
+=====================+===================================================================================================================================================+
| Name                | The document name which is required. Special characters (@ # % & \* ( ) " ' : ; [ ] {} / !) are not allowed in the Name field.                    |
+---------------------+---------------------------------------------------------------------------------------------------------------------------------------------------+
| Categories          | The name of the selected categories.                                                                                                              |
+---------------------+---------------------------------------------------------------------------------------------------------------------------------------------------+
| Language            | The language of the media.                                                                                                                        |
+---------------------+---------------------------------------------------------------------------------------------------------------------------------------------------+
| Content             | The content of the media which is required.                                                                                                       |
+---------------------+---------------------------------------------------------------------------------------------------------------------------------------------------+
| Title               | The display name of the media.                                                                                                                    |
+---------------------+---------------------------------------------------------------------------------------------------------------------------------------------------+
| Creator             | The creator of the media.                                                                                                                         |
+---------------------+---------------------------------------------------------------------------------------------------------------------------------------------------+
| Source              | The source of the media.                                                                                                                          |
+---------------------+---------------------------------------------------------------------------------------------------------------------------------------------------+
| Captions            | Provide the text of the dialogue and important sounds.                                                                                            |
+---------------------+---------------------------------------------------------------------------------------------------------------------------------------------------+
| Audio description   | Provide the narrate track of the media. You can browse and upload another media file from your local device to set it as the audio description.   |
+---------------------+---------------------------------------------------------------------------------------------------------------------------------------------------+
| Alternative text    | Provide the descriptive information about the media.                                                                                              |
+---------------------+---------------------------------------------------------------------------------------------------------------------------------------------------+

Input the information in the fields, and attach existing files from your
local device to the following fields:

-  Content: It must be a *.flv* or *.mp3* file.

-  Captions: It must be a *.srt* or *.mp3* file.

-  Audio description: It must be a *.flv* or *.mp3* file.

Click Save or Save & Close to finish.

The accessible media can be played right after being created.

|image134|

**Details**:

+----------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Button   | Function                                                                                                                                                                                                                               |
+==========+========================================================================================================================================================================================================================================+
|          | Stop the media.                                                                                                                                                                                                                        |
+----------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| /        | Play the media. After clicking this button, |image138| will become |image139| and vice versa.                                                                                                                                          |
+----------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|          | Play the previous media.                                                                                                                                                                                                               |
+----------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|          | Play the next media.                                                                                                                                                                                                                   |
+----------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|          | Listen to the audio description. This icon only appears if you attach another media with the audio description to the Audio description field. After opening the audio description, to back to the original media, click |image140|.   |
+----------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|          | Activate/Deactivate the media caption. If you attach an *.srt* or *.xml* file to the Captions field, the caption will appear when you clicking this button.                                                                            |
+----------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

    **Note**

    You can also attach Captions and Audio description to the uploaded
    media when `editing this
    document <#sect-User_Guide-Actions-Edit_documents>`__. To know how
    to upload a file, see the `Attach files to a
    document <#proc-User_Guide-Add_a_document-Attach_files_to_a_document>`__
    section.

.. |image0| image:: images/affirm.png
.. |image1| image:: images/affirm.png
.. |image2| image:: images/affirm.png
.. |image3| image:: images/affirm.png
.. |image4| image:: images/affirm.png
.. |image5| image:: images/affirm.png
.. |image6| image:: images/affirm.png
.. |image7| image:: images/affirm.png
.. |image8| image:: images/affirm.png
.. |image9| image:: images/affirm.png
.. |image10| image:: images/affirm.png
.. |image11| image:: images/affirm.png
.. |image12| image:: images/affirm.png
.. |image13| image:: images/affirm.png
.. |image14| image:: images/affirm.png
.. |image15| image:: images/affirm.png
.. |image16| image:: images/affirm.png
.. |image17| image:: images/affirm.png
.. |image18| image:: images/affirm.png
.. |image19| image:: images/affirm.png
.. |image20| image:: images/affirm.png
.. |image21| image:: images/affirm.png
.. |image22| image:: images/affirm.png
.. |image23| image:: images/affirm.png
.. |image24| image:: images/affirm.png
.. |image25| image:: images/affirm.png
.. |image26| image:: images/affirm.png
.. |image27| image:: images/affirm.png
.. |image28| image:: images/affirm.png
.. |image29| image:: images/affirm.png
.. |image30| image:: images/affirm.png
.. |image31| image:: images/affirm.png
.. |image32| image:: images/affirm.png
.. |image33| image:: images/affirm.png
.. |image34| image:: images/affirm.png
.. |image35| image:: images/affirm.png
.. |image36| image:: images/affirm.png
.. |image37| image:: images/affirm.png
.. |image38| image:: images/affirm.png
.. |image39| image:: images/affirm.png
.. |image40| image:: images/affirm.png
.. |image41| image:: images/affirm.png
.. |image42| image:: images/affirm.png
.. |image43| image:: images/affirm.png
.. |image44| image:: images/affirm.png
.. |image45| image:: images/affirm.png
.. |image46| image:: images/affirm.png
.. |image47| image:: images/affirm.png
.. |image48| image:: images/affirm.png
.. |image49| image:: images/affirm.png
.. |image50| image:: images/affirm.png
.. |image51| image:: images/affirm.png
.. |image52| image:: images/affirm.png
.. |image53| image:: images/affirm.png
.. |image54| image:: images/affirm.png
.. |image55| image:: images/affirm.png
.. |image56| image:: images/affirm.png
.. |image57| image:: images/affirm.png
.. |image58| image:: images/affirm.png
.. |image59| image:: images/affirm.png
.. |image60| image:: images/affirm.png
.. |image61| image:: images/affirm.png
.. |image62| image:: images/affirm.png
.. |image63| image:: images/affirm.png
.. |image64| image:: images/affirm.png
.. |image65| image:: images/affirm.png
.. |image66| image:: images/affirm.png
.. |image67| image:: images/affirm.png
.. |image68| image:: images/affirm.png
.. |image69| image:: images/affirm.png
.. |image70| image:: images/affirm.png
.. |image71| image:: images/affirm.png
.. |image72| image:: images/affirm.png
.. |image73| image:: images/affirm.png
.. |image74| image:: images/affirm.png
.. |image75| image:: images/affirm.png
.. |image76| image:: images/affirm.png
.. |image77| image:: images/affirm.png
.. |image78| image:: images/affirm.png
.. |image79| image:: images/affirm.png
.. |image80| image:: images/affirm.png
.. |image81| image:: images/affirm.png
.. |image82| image:: images/affirm.png
.. |image83| image:: images/affirm.png
.. |image84| image:: images/affirm.png
.. |image85| image:: images/affirm.png
.. |image86| image:: images/affirm.png
.. |image87| image:: images/affirm.png
.. |image88| image:: images/affirm.png
.. |image89| image:: images/affirm.png
.. |image90| image:: images/affirm.png
.. |image91| image:: images/affirm.png
.. |image92| image:: images/affirm.png
.. |image93| image:: images/affirm.png
.. |image94| image:: images/affirm.png
.. |image95| image:: images/affirm.png
.. |image96| image:: images/affirm.png
.. |image97| image:: images/affirm.png
.. |image98| image:: images/affirm.png
.. |image99| image:: images/affirm.png
.. |image100| image:: images/affirm.png
.. |image101| image:: images/affirm.png
.. |image102| image:: images/affirm.png
.. |image103| image:: images/affirm.png
.. |image104| image:: images/affirm.png
.. |image105| image:: images/affirm.png
.. |image106| image:: images/affirm.png
.. |image107| image:: images/affirm.png
.. |image108| image:: images/affirm.png
.. |image109| image:: images/affirm.png
.. |image110| image:: images/affirm.png
.. |image111| image:: images/affirm.png
.. |image112| image:: images/affirm.png
.. |image113| image:: images/affirm.png
.. | green tick | image:: images/greentick.png
.. | [ Add Document ] | image:: images/adddocumenticon.png
.. |image116| image:: images/template_list.png
.. | [ Upload ] | image:: images/uploadicon2.png
.. |image118| image:: images/uploadfilewindow.png
.. | plus | image:: images/addplusicon.png
.. |image120| image:: images/pdf-viewer.png
.. | [ Source ] | image:: images/sourceicon.png
.. |image122| image:: images/plaintextcontentform.png
.. |image123| image:: images/htmltab.png
.. |image124| image:: images/texttab.png
.. |image125| image:: images/newarticle.png
.. | trash can | image:: images/trashicon.png
.. |image127| image:: images/podcast_form.png
.. |image128| image:: images/podcastscreen.png
.. |image129| image:: images/samplenodeformcompleted.png
.. |image130| image:: images/record-properties.png
.. |image131| image:: images/processproperties.png
.. |image132| image:: images/addnewkofax.png
.. |image133| image:: images/accessible_media.png
.. |image134| image:: images/play-media.png
.. |image135| image:: images/play-button.png
.. |image136| image:: images/pause-button.png
.. |image137| image:: images/back-the-original-video.png
.. |image138| image:: images/play-button.png
.. |image139| image:: images/pause-button.png
.. |image140| image:: images/back-the-original-video.png
