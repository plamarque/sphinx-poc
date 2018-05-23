Document Viewer
===============

**The viewable document types**

The Documents application allows users to build custom content types and
provides some built-in content types. It also provides a viewer for
common file types so users can read Office documents, view images or
play videos directly from the activity stream.

When a document has a preview, a part of it is displayed, if not a
thumbnail icon is displayed:

|image0|

When clicking to preview, here is what we got in the two cases:

|image1|

The following types are viewable i.e has a preview:

-  Printable files: *pdf*, *doc* (and other Office files) or any other
   type of files
   `JODConverter <#PLFAdminGuide.Configuration.JODConverter>`__
   supports. See the full list of types at `JODConverter, Administrator
   Guide <#PLFAdminGuide.Configuration.JODConverter>`__.

-  Images: *png, jpg, jpeg, gif*.

-  Audios/Videos: *mp3, mp4*.

-  ECMS content, either custom or built-in templates, such as a *web
   content* template.

For these viewable types, when you click a document preview thumbnail in
the Activity Stream or select the *View Document* menu from Documents in
the left navigation pane, the **Document Viewer** opens. The viewer
provides a large viewing area and some functions, such as Search,
Download and Print.

    **Tip**

    To exit the Viewer, hit *Esc* key or click **X** icon at the top
    right corner.

    **Note**

    The Comment pane, where you can comment on or like a post, is only
    available when you view a document in the Activity Stream.

    If the document is an unknown type, you must download it to your
    local machine and open it with another application.

**Office documents and pdf files**

You can always view pdf files, whereas Office documents require
`JODConverter <#PLFAdminGuide.Configuration.JODConverter>`__ to be
installed on the server. If you cannot view an MS Word file, for
example, contact your administrators.

For these file types, the Document Viewer provides maximized reading
estate and all the functions listed.

|image2|

-  **Page Navigator**

Although you can simply scroll to go to another page, the Page Navigator
provides many page selectors (e.g. previous, next, first and last page
links, page number selector). You can also show/hide the Page Thumbnail
pane by clicking the leftmost icon in the toolbar. Click it again to
close it.

|image3|

-  **Search**: Click the Search icon |image4| to open the Search bar and
   click it again to exit.

|image5|

-  **Download**: Click the Donwload icon |image6| to download the file.

-  **Full screen mode**: Click the *Switch to Presentation Mode* icon
   |image7| to read in full screen. Hit *Esc* key to exit this mode.

-  **Print**: Click the *Tools* icon |image8| then select *Print*.

-  **Comment**: You will see the Comment area on the right side when you
   open the viewer. If it is hidden, you can bring it back by clicking
   the rightmost arrow icon.

|image9|

-  **Like**: In the Comment area, click the *Like* icon |image10| to
   like the post. Click it again to unlike.

**Images, Audios and Videos**

For viewable media types, the available functions are Download, Comment
and Like.

|image11|

    **Note**

    Audio/Video playback may require appropriate browser plugins. A
    message like "*Video format or MIME type is not supported*\ "
    indicates that you may need to install or enable some plugins for
    that media type.

**ECMS Content**

If the document is ECMS Content, it is viewable. The following
screenshot shows *illustrated web content*, which is one of the built-in
templates.

|image12|

.. |image0| image:: images/ecms/preview_thumbnail.png
.. |image1| image:: images/ecms/preview_mode.png
.. |image2| image:: images/ecms/doc_viewer_demo_pdf.png
.. |image3| image:: images/ecms/doc_viewer_page_selectors.png
.. |image4| image:: images/common/search_icon.png
.. |image5| image:: images/ecms/doc_viewer_search.png
.. |image6| image:: images/ecms/doc_viewer_download_icon.png
.. |image7| image:: images/ecms/doc_viewer_full_screen_icon.png
.. |image8| image:: images/ecms/doc_viewer_tools_icon.png
.. |image9| image:: images/ecms/doc_viewer_comment_area.png
.. |image10| image:: images/common/like_icon.png
.. |image11| image:: images/ecms/doc_viewer_demo_img.png
.. |image12| image:: images/ecms/doc_viewer_demo_ecms_content.png
