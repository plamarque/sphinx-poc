Creating a calendar
===================

You may create a `personal
calendar <#PLFUserGuide.ManagingYourCalendars.CreatingCalendar.PersonalCalendar>`__
or `group
calendar <#PLFUserGuide.ManagingYourCalendars.CreatingCalendar.GroupCalendar>`__
that can be shared with specific users or groups to your desires. You
can also create a calendar which is synchronized with a `remote
calendar <#PLFUserGuide.ManagingYourCalendars.CreatingCalendar.RemoteCalendar>`__.

**Creating a personal calendar**

    **Note**

    All personal calendars will be put in the **Personal Calendars**
    pane.

Click |image0|, then select Add Calendar from the drop-down menu.

Fill in fields of the Details tab.

**Details:**

+-----------------------+----------------------------------------------------+
| Field                 | Description                                        |
+=======================+====================================================+
| Display Name          | The calendar name which is displayed.              |
+-----------------------+----------------------------------------------------+
| Description           | The brief description of the calendar.             |
+-----------------------+----------------------------------------------------+
| Time Zone             | The display time zone for the calendar activities  |
|                       | which cannot be edited. However, you can change    |
|                       | the time zone in your `calendar                    |
|                       | settings <#PLFUserGuide.ManagingYourCalendars.Edit |
|                       | ingCalendarSettings.TimeZone>`__.                  |
+-----------------------+----------------------------------------------------+
| Color                 | The display color of the calendar activities that  |
|                       | can be personalized.                               |
+-----------------------+----------------------------------------------------+

    **Note**

    If you select the `Show in Groups <#ShowInGroupsForm>`__ tab, then
    click |image1| to define specific groups and click |image2|, the
    calendar will be put in the **Group Calendars** category, not in the
    **Personal Calendars** category.

Click Save to finish your creation.

**Creating a group calendar**

    **Note**

    All group calendars will be put in the **Group Calendars** pane.

Follow steps as stated in `Creating a personal
calendar <#PLFUserGuide.ManagingYourCalendars.CreatingCalendar.PersonalCalendar>`__
to give details for your new calendar.

Select the Show in Groups tab.

Select groups that contain your created calendar. The users of the
selected groups can only view this calendar.

**i.** Click |image3| to open the Group Selector form. This form will
help you select a group that you want to share.

**ii.** Click your desired group, then select |image4| to add the
defined group.

**iii.** Click |image5| or |image6| to grant permissions to specific
users or memberships respectively from the selected group.

    **Note**

    -  If you set the \* membership in the User able to edit calendar
       column, all users of the selected group will be able to edit this
       calendar, regardless of their membership role.

    -  You can select more users/memberships by repeating the above
       steps. The selected users/memberships will be updated in
       corresponding textboxes.

    -  You can delete your selected users/memberships manually in the
       textboxes or click |image7| to remove the permissions.

Click Save to finish creating your new group calendar.

**Creating a remote calendar**

    **Note**

    To create a remote calendar in the **Calendar** application
    successfully, you need to learn about the calendar settings of the
    relevant provider. For more information about types of remote
    calendars, see `here <#MoreAboutiCalCalDAV>`__.

Click |image8|, then select Remote Calendar from the drop-down menu. The
Subscribe Calendar form appears.

Select the type of the remote calendar: iCalendar or CalDAV.

Enter the URL linking to your calendar server in the URL field.

Click Next to go to the Remote Calendar form.

Fill in the fields. The asterisk (\*) indicates the field is mandatory.

Tick the Use Authentication checkbox, then enter the username and
password of your remote calendar server if the remote server requires
verification.

Click Save to accept your creation.

    **Note**

    After creating a remote calendar, you can ONLY VIEW all events and
    tasks which are created in the remote calendar server right in the
    **Calendar** application by clicking it. To get the updates, hover
    your cursor over the remote calendar, then click |image9| to select
    Refresh from the drop-down menu.

**More information about types of remote calendars**:

-  **iCalendar**:

iCalendar provides a link to an online .ics file from another calendar
servers, such as Google Calendar, Yahoo Calendar, or eXo Calendar
(including public URL or private URL).

An example of a Google Calendar URL (in iCal format):

`https://calendar.google.com/calendar/ical/en.tn%23holiday%40group.v.calendar.google.com/public/basic.ics <http://calendar.google.com/calendar/ical/en.tn%23holiday%40group.v.calendar.google.com/public/basic.ics>`__

-  **CalDAV**:

CalDAV is an open protocol that allows you to access calendars via
WebDAV. With CalDAV, you can publish and subscribe to calendars, share
them collaboratively, synchronize among multiple users or devices.

**Google**: https://apidata.googleusercontent.com/caldav/v2/calid/events
where ``calid`` is the calendar id to be accessed.

**Yahoo**:
https://caldav.calendar.yahoo.com/dav/your_yahoo_account@yahoo.com/Calendar/calendar_name/

**How to import a Google calendar?**:

Below an example of how to import a Google calendar to PRODUCT:

Go to your Google calender interface and select the calendar you wish to
import to PRODUCT.

Click on options button |image10| of the chosen calendar and then select
Settings and sharing.

|image11|

An interface Settings appears, scroll down to the section Integrate
calendar and copy your calendar's public link in iCal format.

|image12|

Go to the calendar interface in PRODUCT and click on the |image13| then
on Remote calendar.

Paste the iCal link to the field URL.

Click on Next to move to the form in calendar settings. Fill in the
needed fields.

    **Note**

    If the imported remote calendar is not public, you should input your
    google account credentials in the "Authentication" section to enable
    the import procedure.

.. |image0| image:: images/calendar/add_icon_calendar.png
.. |image1| image:: images/common/select_everyone_icon.png
.. |image2| image:: images/calendar/add_button.png
.. |image3| image:: images/common/select_group_icon.png
.. |image4| image:: images/calendar/add_button.png
.. |image5| image:: images/common/select_user_icon.png
.. |image6| image:: images/common/select_role_icon.png
.. |image7| image:: images/common/delete_icon.png
.. |image8| image:: images/calendar/add_icon_calendar.png
.. |image9| image:: images/calendar/calendar_setting_icon.png
.. |image10| image:: images/calendar/options_button.png
.. |image11| image:: images/calendar/settings_sharing_option.png
.. |image12| image:: images/calendar/public_address_ical.png
.. |image13| image:: images/calendar/add_icon_calendar.png
