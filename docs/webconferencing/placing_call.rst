.. _MakingVideoCalls:

Placing a call
==============

Starting from the 5.0 version of eXo Platform it is possible to make
one-to-one video calls through the Web Conferencing add-on.


.. warning:: * The video call functionality operates with the standard
				`WebRTC <https://webrtc.org/>`__ and requires modern web browsers.
			 * Web Conferencing is not supported for the browser IE11. Check the
				full list of supported web browsers in `this
				file <https://www.exoplatform.com/terms-conditions/supported-environments.pdf>`__.
			 * One-to-one video calls are not available for mobile devices.

To use the Web Conferencing functionality and make video call with
another user, you just need to click on the Call button |image0|.

The Call button is available in many places:

-  When moussing over a user's avatar in the activity stream.

   |image1|

-  When accessing a user's profile, near the user's display name.

   |image2|

-  In the chat room.

   |image3|

-  In mini chat room windows.

   |image4|

Pressing the Call button emits a call and generates a separate browser
window which displays your face if you activated your camera in your
last call. It also emits ringtone, which indicates that an outgoing call
is in progress. The ringtone stops when the callee answers the call.

|image5|


 .. note:: 1. If you are using the feature for the first time, when you press the
			Call button, the call screen appears and contains a popup asking if
			you want to allow the browser to access your microphone and camera:
			**In Firefox:**

			|image6|

			**In Chrome:**

			|image7|

		   2. To process to the call, you need to click on the Allow button.

		   3. If you press on Block or Don't Allow, the call is interrupted:

			|image8|

		   4. Video sharing and microphone settings remember your previous status.
			For example, if you have muted your microphone in a previous
			session, the call starts with sound muted. If you have unshared your
			camera, the call starts without streaming your video stream.

When starting the call i.e. after pressing the Call button, at first it
shows your camera stream, and when communication is established with
your partner, it displays their video stream (if they have enabled it).
After that, your own video stream is miniaturised on the bottom-right
corner.

The video call window contains three buttons to control the call:

-  |image9|: This allows you to mute/unmute your audio.

-  |image10|: This allows you to share/unshare your video stream.

-  |image11|: This allows you to end the video call. Clicking on this
   button terminates the call and closes the call window.

   It is also possible to terminate the call by clicking on the Close
   button |image12| of the call screen's web page.

If your callee declines the call, a a hang-up sound is played on your
local output and then the call window displays a message which indicates
that the call has been stopped.

|image13|

.. _Multiple-connectors:

Multiple connectors
~~~~~~~~~~~~~~~~~~~~~~~~~

If many connectors are installed and enabled for Web Conferencing, the
Call button will be a pulldown which allows to select which provider
that you want to use.

This pulldown **remembers your last selected settings**, and displays
these by default.

|image14|

For each call provider who needs an IM account, a new entry is added in
the IM-field pulldown of users’ profiles.

|image15|

.. |image0| image:: images/webconf/call_button.png
.. |image1| image:: images/webconf/user_popover.png
.. |image2| image:: images/webconf/user_profile.png
.. |image3| image:: images/webconf/chat_room.png
.. |image4| image:: images/webconf/mini_chat_room.png
.. |image5| image:: images/webconf/webconf.png
.. |image6| image:: images/webconf/permission2.png
.. |image7| image:: images/webconf/permission.png
.. |image8| image:: images/webconf/no_permission.png
.. |image9| image:: images/webconf/first_button.png
.. |image10| image:: images/webconf/second_button.png
.. |image11| image:: images/webconf/third_button.png
.. |image12| image:: images/webconf/close_button.png
.. |image13| image:: images/webconf/stopped_call.png
.. |image14| image:: images/webconf/pulldown.png
.. |image15| image:: images/webconf/IM_field.png
