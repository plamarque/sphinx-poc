BRAND\_TASK\_MANAGEMENT overview
================================

To use your BRAND\_TASK\_MANAGEMENT application effectively, there are
some terms that you should be aware of:

-  **Projects**: Containers of tasks.

-  **Management views**: Two views (Board and List) that provide you
   with different ways to manipulate your tasks.

-  **Project workflow**: The list of statuses that tasks in a project
   can take. By default, a new project will have the following workflow:
   *To Do, In Progress, Waiting On* and *Done*. Alternatively, you can
   change the project workflow later in the Board view.

       **Note**

       Changing the default workflow for new projects is done only by
       the administrator, see `this
       section <#PLFAdminGuide.Configuration.TaskManagement>`__ for more
       details.

-  **Sub-project**: A project can have any number of sub-projects and a
   sub-project can also have an unlimited number of smaller
   sub-projects. These sub-projects will inherit permission and workflow
   from their parent project at the creation time and you can change
   them later.

-  **Space project**: For each new space, a project with the same name
   will be automatically created when the BRAND\_TASK\_MANAGEMENT
   application is added to the space.

The BRAND\_TASK\_MANAGEMENT overview is divided into three main areas,
including left, central and right panes.

|image0|

**The left pane**

|image1|

This pane includes three sections:

-  **Tasks**: manages tasks individually by left filters. These filters
   are:

   -  *Incoming*: filters tasks that are not yet assigned to a project.
      This filter also excludes completed tasks by default, but you can
      change this by using the top
      `Filter <#PLFUserGuide.WorkingWithTasks.ManageTask.Filtering>`__
      feature.

   -  *All Tasks*: shows unfiltered list of all tasks assigned to the
      current user.

   -  *Overdue*: filters tasks with a past due date.

   -  *Today*: filters tasks that are due today.

   -  *Tomorrow*: filters tasks that are due tomorrow.

   -  *Upcoming*: filters tasks that are due in future.

-  **Projects**: manages tasks by projects. Specifically, you can manage
   the workflow of tasks that are assigned to a project.

-  **Labels**: manages tasks by labels. You can set any label on a task
   to classify it for you to manage your tasks more easily.

**The central pane**

This pane is used to display tasks filtered via the left pane and `top
Filter <#PLFUserGuide.WorkingWithTasks.ManageTask.Filtering>`__. In case
you are in a project, a *Board* view is provided so that you can manage
the project's tasks more easily.

**The right pane**

This pane displays details of the task that is selected from the central
pane where you can modify any information of the task.

    **Note**

    Inside spaces, the BRAND\_TASK\_MANAGEMENT overview is similar as
    above, but the project list is filtered to display only projects
    that are accessible for the members of the spaces. Besides, there
    will be no *Incoming* filter on the left menu and clicking on a
    label will display only the tasks with the selected labels in the
    spaces' projects.

.. |image0| image:: images/taskmanagement/overview.png
.. |image1| image:: images/taskmanagement/left_pane.png
