.. _Search-Documents:

=======================
Searching for documents
=======================

To search for documents only, you first need to select Documents from
the left panel. You are then redirected to the Documents page. Here, you
can perform the search types:

-  :ref:`Quick search <QuickSearch>`

-  :ref:`Advanced search <AdvancedSearch>`

-  :ref:`Saved queries <SearchingWithSavedQueries>`
   
.. _QuickSearch:   

Quick search
~~~~~~~~~~~~~

With the quick search, you can directly type a search term in the search
textbox. All documents, whose keywords are matched with the search term,
are retrieved and listed in the results form.

1. Enter a keyword into the search textbox.

|image0|

2. Click |image1| to perform your search; Or, press the **Enter** key.

The search results will be displayed right in the main view. The search
results are empty if no document contains the search keyword.

|image2|

**In which:**

+----------------+-----------------------------------------------------------+
| **Fields**     | **Description**                                           |
+================+===========================================================+
| Type           | Groups the content by its type together. The ascending    |
|                | order is set by default. By clicking Type, the order type |
|                | will be changed into descending, and vice versa.          |
+----------------+-----------------------------------------------------------+
| Name           | Displays the document content which matches with your     |
|                | search term.                                              |
+----------------+-----------------------------------------------------------+
| Score          | The appearance frequency of your search term in the       |
|                | content. The higher score is, the more your search term   |
|                | appears in the content.                                   |
+----------------+-----------------------------------------------------------+
| Action         | Two actions you can do the content, including:            |
|                |                                                           |
|                | -  Click |image5| corresponding to the document you want  |
|                |    to view;                                               |
|                |                                                           |
|                | -  Or, click |image6| to go to the folder which contains  |
|                |    the relevant document.                                 |
|                |                                                           |
                                                                            
+----------------+-----------------------------------------------------------+

.. _Refine-quick-search-tags:

Refine quick search using tags
-------------------------------

You can refine the search results by selecting one or many `documents
tags <#PLFUserGuide.ManagingYourDocuments.WorkingWithBasicActions.TaggingDocument>`__.

This allows you to display in the search results documents:

-  Containing the used keyword for search.

-  Tagged by the selected tags.

For that purpose, proceed as follows:

1. Ensure that the sidebar is diplayed in left menu of the documents application, if not refer to this
:ref:`link <#PLFUserGuide.ManagingYourDocuments.OrganizingYourContent.CustomizingYourPreferences>` to display it.

|image7|

2. Click |image8| to display all the used tags for documents.

|image9|

3. Select one or many tags to refine the search results.

|image10|

 .. note::   To be able to refine your search using tags, you should :ref:`add tags <#PLFUserGuide.ManagingYourDocuments.WorkingWithBasicActions.TaggingDocument>`
    when uploading/adding contents and files to the documents application, otherwise, the tag cloud will be empty.

.. _Advanced-search:

Advanced search
~~~~~~~~~~~~~~~~~

1. Click |image11| on the sidebar. To follow this way, you need to :ref:`enable sidebar <#EnableSideBar>` first.

|image12|

2. Click |image13| to open the **Advanced Search** form.

|image14|

The tabs in this form offer different search functions:

-  :ref:`Searching by Name <SearchingByName>`

-  :ref:`Searching with constraints <SearchingWithConstraints>`

-  :ref:`Searching by creating a new query <SearchingByNewQuery>`

-  :ref:`Searching by existing queries <SearchingByExistingQueries>`

.. _SearchingByName:

Searching by Name
-------------------

Use the **Searching by Name** tab to search nodes by name as follows:

1. Enter the exact name you wish to search in the **Content Name** field.

2. Click **Search**.

* Results will return with the message No results found if there is no content with the entered name.

* Results will be returned in the **Search Results** tab if the requested name is found.

.. _SearchingWithConstraints:

Searching with constraints
---------------------------

This search enables you to search with more constraints to limit the
returned results.

Extra search constraints are entered in the **Advanced Search** tab of
the **Advanced Search** form.

|image15|

The **Current location** field is not editable. It shows the path
selected to search.

1. Enter search terms in the **A word or phrase in content** field.

2. Select the **Operator**:

- Select **And** operator to only return results that meet both the
   search terms and the entered constraints (see Step 3).

-  Select **Or** operator to return results that meet *either* the
   search terms or the entered constraints (see Step 3).

3. Click **Show/Hide Constraint Form** to add more constraints.

A further constraint options window will appear.

|image16|

**In which:**

+------------+---------------------------------------------------------------+
| Item       | Description                                                   |
+============+===============================================================+
|            | Adds more than one constraint with either of two operators    |
|            | (**And** and **Or**).                                         |
+------------+---------------------------------------------------------------+
|            | Adds a constraint to search by a property with specific       |
|            | values.                                                       |
+------------+---------------------------------------------------------------+
|            | Adds a constraint to search by a property that contains one   |
|            | of the word in the keyword.                                   |
+------------+---------------------------------------------------------------+
|            | Adds a constraint to search by a property that does not       |
|            | contain the keyword.                                          |
+------------+---------------------------------------------------------------+
|            | Adds a constraint to search by a duration of date (created,   |
|            | modified).                                                    |
+------------+---------------------------------------------------------------+
|            | Adds a constraint to search by a document type, including     |
|            | File, Article, Podcast, Sample node, File Plan, Kofax.        |
+------------+---------------------------------------------------------------+
|            | Adds a constraint to search by categories.                    |
+------------+---------------------------------------------------------------+
|            | Adds a value/property.                                        |
+------------+---------------------------------------------------------------+

4. Select the constraint operator (**And/Or**).

5. Add the required constraints using one of the following methods:

-  :ref:`Adding a constraint for exact values <AddingConstraintForExactValues>`

-  :ref:`Adding a constraint including or excluding values <AddingConstraintInCludingValues>`

-  :ref:`Adding a constraint by date <AddingConstraintByDate>`

-  :ref:`Adding a constraint by document type <AddingConstraintByDocumentType>`

-  :ref:`Adding a constraint by category <AddingConstraintByCategory>`

6. Click **Add** to add any/all activated constraints.

The constraints will be converted to an **SQL** query and displayed in
the search form.

|image17|

-  Remove unnecessary constraints by clicking |image18|

7. Click **Search** to launch the search. Results will be displayed in the
**Search Results** tab.

8. Click **Save** and put a name for this search configuration if you want
to save it to use in future.

The followings are methods to add the required constraints.

.. _AddingConstraintForExactValues:

**Adding a constraint for exact values**

1. Tick the checkbox that corresponds to the constraint you want.

2. Enter the property you want to locate, or click |image19|

A list of possible properties appears.

|image20|

3. Select a property from the list and click Add. The selected property
will populate the **Property** field.

4. Define the property value to search for by entering a value into the
**Contain Exactly** field, or click | Find exactly |.

The **Filter Form** with all pre-existing values for your selected
property will appear.

-  If the value you require is in the list, select it and click **Select**.

-  If the value you require is not in the list, enter it in the **Filter** field and click | corresponding |. The value will populate
   the **Contain Exactly** field of the constraints form.

|image23|

.. _AddingConstraintInCludingValues:

**Adding a constraint including or excluding values**

1. Tick the checkbox corresponding to the **Contain** or **Not Contain** constraint, as appropriate.

2. Enter the required property in the **Property** field, or click |image21| (refer to **Step 2** in the :ref:`Adding a constraint for exact values <AddingConstraintForExactValues>` section for more information).

3. Enter the required values in the **Contain** or **Not Contain** fields.

.. _AddingConstraintByDate:

**Adding a constraint by date**

1. Tick the checkbox beside the field with the drop-down menu (below the
**Property** entries).

2. Define the search condition from the drop-down list
(**Created**/**Modified**).

3. Click the **From** field.

A small calendar will appear.

|image25|

4. Select the date you want to use as a constraint.

5. Repeat the above steps for the **To** field.

The selected dates will populate the **From** and **To** fields in the
**Add constraint** form.

.._AddingConstraintByDocumentType:

**Adding a constraint by document type**

1. Tick the checkbox beside the **Document Type** field.

2. Enter the document type you want to search, or click |image26| to open a list of document types.

|image27|

3. Tick the checkbox corresponding to your desired document type, then
click **Save**.

The selected document type will populate the **Document Type** field.

.. _AddingConstraintByCategory:

**Adding a constraint by category**

1. Tick the checkbox beside the **Category** field.

2. Enter the category you want to search, or click |Add category| for a list of categories.

3. Click |image29| that corresponds to your desired category.

The selected category will populate the **Category** field.

.. _SearchingByNewQuery:

Searching by creating a new query
------------------------------------

You need knowledge of the structure of query statements to configure a
search using the parameters on the **New Query** tab.

1. Enter a unique name for this query in the **Name** field.

2. Select a query type from the drop-down menu: **SQL** or **xPath**.

3. Enter a query statement.

4. Click Search to perform the search and display the results in the Search
Results tab; Or, click Save to save the search query to the Saved Query tab.

.. _SearchingByExistingQueries:

Searching by existing queries
-------------------------------

This tab lists all saved search queries that you have access rights to
use.

|image30|

-  Click |image31| to perform the search. You will see results in the
   **Search Results** tab.

-  Click |image32| to edit the query statement. The query form will
   appear like when creating a query (see the :ref:`Searching by creating a new query <SearchingByNewQuery>` section); however, you cannot edit the name of the saved search.

-  Click |image33| to delete a query (provided you have the access
   rights to that query).

Searching with saved queries
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Do the followings to perform a search with saved queries:

1. Click |image34| on the sidebar to see the list of existing queries.

|image35|

2. Launch, modify or delete the queries as required (see the :ref:`Searching by
creating a new query <SearchingByNewQuery>` section for more information).

3. Filter results with the entries in the **All Items** and/or **Filter by
Type** panes on the left of the tab. Items matching the selections will
appear in the right pane.

4. Click |image36| to view the file or click |image37| to go to the file location.

.. |image0| image:: images/search/quick_search_documents.png
.. |image1| image:: images/common/search_icon.png
.. |image2| image:: images/search/search_results_form.png
.. |image3| image:: images/common/view_icon.png
.. |image4| image:: images/search/goto_folder_icon.png
.. |image5| image:: images/common/view_icon.png
.. |image6| image:: images/search/goto_folder_icon.png
.. |image7| image:: images/search/documents_sidebar.png
.. |image8| image:: images/search/tag_cloud_btn.png
.. |image9| image:: images/search/tags_cloud.png
.. |image10| image:: images/search/multitag_search.png
.. |image11| image:: images/common/search_icon.png
.. |image12| image:: images/search/saved_searches_sites_management.png
.. |image13| image:: images/common/search_icon.png
.. |image14| image:: images/search/document_advanced_search.png
.. |image15| image:: images/search/document_advanced_search_tab.png
.. |image16| image:: images/search/document_advanced_search_more_constraints.png
.. |image17| image:: images/search/constraint_added_search_form.png
.. |image18| image:: images/common/delete_icon.png
.. |image19| image:: images/common/plus_icon.png
.. |image20| image:: images/search/select_property_form.png
.. |image21| image:: images/common/plus_icon.png
.. | corresponding | image:: images/common/plus_icon.png
.. |image23| image:: images/search/contain_exactly_populated.png
.. | Add Property | image:: images/common/plus_icon.png
.. |image25| image:: images/search/date_search_condition.png
.. |image26| image:: images/common/plus_icon.png
.. |image27| image:: images/search/document_type_list.png
.. | "Add category" | image:: images/common/plus_icon.png
.. |image29| image:: images/common/select_icon.png
.. |image30| image:: images/search/saved_search_query_tab.png
.. |image31| image:: images/search/execute_icon.png
.. |image32| image:: images/common/edit_icon.png
.. |image33| image:: images/common/delete_icon.png
.. |image34| image:: images/common/search_icon.png
.. |image35| image:: images/search/saved_search_panel.png
.. |image36| image:: images/common/view_icon.png
.. |image37| image:: images/search/goto_folder_icon.png
