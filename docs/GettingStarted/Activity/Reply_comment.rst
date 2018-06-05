.. _Replying-comments:

Replying to comments
====================

In addition to `Liking comments <#Liking-comments>__` feature in eXo Platform, it is possible to reply to a comment.

Under each comment, a Reply button appears allowing you to reply to that
comment:

|image0|

When you click on the Reply link, a comment composer appears with your
avatar just below the last reply if it exists:

|image1|

When you click on the comment composer to type your message, a rich text
editor toolbar appears allowing you to format your text:

|image2|

When more than two replies are posted to a comment, the replies are
collapsed and a link to View all X replies (X is the total number of
replies) is displayed allowing to view the whole replies.

|image3|


    .. note:: Some other details about the reply to comment feature:
    -  There is only one level of replies, it is the reply to comment. There is not a reply to a reply.
    -  Deleting a comment with replies induces the replies deletion.
    -  In addition to activity stream comments, the reply to comment feature is available for activities of these applications: Documents preview, forum and tasks.
    -  Same as for comments, it is possible to like replies except in tasks application.

Reply to comment for Forum application
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

As mentioned above, the reply to comment is also available for forum
posts activities:

-  When you reply to a comment in the activity related to a forum, the
   reply will appear as comment in the forum application which quotes
   the original comment.

   |image4|

-  When you post a reply to forum topic and quote the previous post, it
   will appear as a reply to the first comment of level 1 in the
   corresponding activity.


    .. note:: When you use the quote option |image5| of the CKeditor toolbar in the reply to comment, it will be considered as a simple quote.
				|image6|

Reply to comment notifications
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

When someone replies to your comment, you receive an onsite notification
which contains:

-  The avatar of the user who replied to your comment.

-  A label: "UserA has replied on one of your comments".

-  The reply timestamping.

-  The comment to which the user replied and if the comment is too long,
   an ellipsis of it.

|image7|

All the watchers of the activity i.e it's likers and the space's members
if it is a space activity receive a simple comment notification.

When a user replies to an another user's comment to your activity:

-  The user who commented your activity receives a reply to comment
   notification.

-  You receive a simple comment notification.

If the email notification is enabled, you will receive an email when
someone replies to your comment which contains:

-  The label "User X has replied to one of your comments. See below:"

-  Your comment content.

-  The source link i.e the platform link.

-  The user name who replied followed by his reply.

|image8|

A new line in `my
notifications <#PLFUserGuide.ManagingYourPersonalApplications.NotificationSettings>`__
settings is added to manage reply to comment notifications:

|image9|

Default values are:

-  Send me an email right away: checked.

-  Send me a digest email: Daily.

-  See on site: checked.

.. |image0| image:: images/platform/reply_comment.png
.. |image1| image:: images/platform/reply_comment_area.png
.. |image2| image:: images/platform/reply_comment_area_CKeditor.png
.. |image3| image:: images/platform/more_replies.png
.. |image4| image:: images/platform/forum_replies.png
.. |image5| image:: images/platform/quote.png
.. |image6| image:: images/platform/simple_quote.png
.. |image7| image:: images/platform/notification.png
.. |image8| image:: images/platform/email_notif.png
.. |image9| image:: images/platform/notification_line.png
