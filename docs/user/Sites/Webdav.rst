Using WebDAV
============

In PRODUCT, you can use WebDAV to perform actions on a website easily,
quickly and efficiently without accessing it directly on web browsers.
Each website managed by WebDAV will be displayed as a folder.

To manage site content using WebDAV, follow either of two ways:

**The first way**

You need to connect to your WebDAV clients. See
`WebDAV <#PLFUserGuide.AdministeringeXoPlatform.WebDAV>`__ for more
details.

It is assumed that you want to access the ACME site using WebDAV, simply
use the URL:
`http://mycompany.com:port/rest/private/jcr/repository/collaboration/sites/acme <http://mycompany.com:8080/rest/private/jcr/repository/collaboration/sites/acme>`__
into the address bar. After successul login, the ACME site appears as a
folder.

|image0|

**The second way**

This way can be done through **Sites Management.**

Click |image1| on the top navigation bar, then select Content Sites
Explorer from the drop-down menu.

Click the Show Drives button, then select Sites Management.

|image2|

You will see all sites listed in the left sidebar.

|image3|

Right-click your desired site to view with WebDAV, and select Download
and Allow Edition from the menu.

The selected site will be shown in WebDAV.

|image4|

In this view, you can access documents in the directories that are
linked to the web server.

**Adding new content to a specific site**

This function enables you to copy web content, such as an *.html* file,
from your local device to a *web content* folder of a site.

Access a site via WebDAV, then go to a **web content** folder of the
site.

Copy the web content on your local system into this folder.

The copied file will be converted to web content that is viewable by
WebDAV automatically. The content is converted to a directory containing
*CSS, documents, js and media.*

After the new content is added, it can be viewed as a folder in WebDAV
or as a page using a web browser.

**Deleting web content**

This function enables site administrators to delete web content files
separately or in batches.

Navigate to the folder that contains the content you want to remove.

Right-click the content files or directories (hold the *Ctrl* key to
select multiple files at once), and select Delete from the drop-down
menu.

The selected files will be removed from the site.

.. |image0| image:: images/ecms/webdav_acme_folder.png
.. |image1| image:: images/common/administration_navigation.png
.. |image2| image:: images/ecms/sites_management_drive.png
.. |image3| image:: images/ecms/sites_list.png
.. |image4| image:: images/ecms/webdav_site_view.png
