Queries
=======

In Advanced, select Queries. You will be directed to the **Queries**
panel as below:

|image0|

Here, you can do certain actions on the queries as follows:

-  `Editing a
   query <#PLFUserGuide.AdministeringeXoPlatform.ContentAdministration.WorkingWithAdvancedConfiguration.Queries.EditingQuery>`__
   |image1|

-  `Deleting a
   query <#PLFUserGuide.AdministeringeXoPlatform.ContentAdministration.WorkingWithAdvancedConfiguration.Queries.DeletingQuery>`__
   |image2|

-  `Adding a new
   query <#PLFUserGuide.AdministeringeXoPlatform.ContentAdministration.WorkingWithAdvancedConfiguration.Queries.AddingNewQuery>`__
   |image3|

Editing/Deleting a query
------------------------

**Editing a query**

Click |image4| in the Action column to open the Edit Query form.

|image5|

Edit the properties of the selected query.

    **Note**

    In the *Permissions* field, if you set the \* membership for a
    group, all users of the group will be able to access this saved
    query, regardless of their membership role.

Click Save to accept all changes.

**Deleting a query**

Simply click |image6| in the Action column, then select **OK** in the
confirmation message.

Adding a new query
------------------

Click Add Query to open the Add Query form.

|image7|

Enter a query name into the Query Name field that is required.

Select the query type from the Query Type drop-down menu.

-  xPath (XML Path Language) is a language for selecting nodes. For
   example, ``/jcr:root/Documents/Live``.

-  SQL (Structured Query Language) is a database computer language.

Enter the statement for the query that must be unique.

Check or uncheck the Enable Cache Results option. If you tick this
checkbox, for the first time you use this query to search, the result
will be cached. For the second time you search using this query, it will
show the cached results. After 10 minutes, the cache will be removed.

For example, you have the **Test** query with the **//element (\*,
nt:file)**. In Sites Explorer, you have a ``nt:file`` document named
``File1``. When you execute the query ``Test``, only the ``File1``
document is shown. After that, create a ``nt:file`` document named
``File2`` and execute the query ``Test``, only the ``File1`` document is
listed. After 45 minutes, the cache will be removed. When you execute
the query ``Test``, ``File1`` and ``File2`` will be listed.

Select permissions for a group that can use this query by clicking
|image8|.

    **Note**

    In the *Permissions* field, if you set the \* membership for a
    group, all users of the group will be able to access this saved
    query, regardless of their membership role.

Click Save to finish adding a new query.

.. |image0| image:: images/ecms/queries_panel.png
.. |image1| image:: images/common/1.png
.. |image2| image:: images/common/2.png
.. |image3| image:: images/common/3.png
.. |image4| image:: images/common/edit_icon.png
.. |image5| image:: images/ecms/edit_query_form.png
.. |image6| image:: images/common/delete_icon.png
.. |image7| image:: images/ecms/add_query_form.png
.. |image8| image:: images/common/plus_icon.png
