.. _administrating-webconf:

Administrating Web Conferencing
===============================

The Web Conferencing add-on comes with an administrative interface which
allows administrators to enable/disable providers and configure
settings.

|image0|


.. note:: In the previous illustration, multiple providers are available,
			which is not the case in the standard Web Conferencing add-on that
			comes built-in with eXo Platform. In standard distributions, only WebRTC
			connector is available. Other providers will be available on
			different add-ons, but they are not supported.

To access the administration page:

-  You should be part of the group **platform/administrators**.

-  Click |image1| --> Web Conferencing on the top navigation bar.

|image2|

To enable or disable a provider, you just need to move over the radio
button of the Active field:

|image3|

To add a server for the WebRTC provider, you should click on |image4|
button and, a form WebRTC Settings appears.

|image5|

Click on the |image6| button to add an
`ICE <https://en.wikipedia.org/wiki/Interactive_Connectivity_Establishment>`__
server URL. It could be `STUN <https://en.wikipedia.org/wiki/STUN>`__ or
`TURN <https://en.wikipedia.org/wiki/Traversal_Using_Relays_around_NAT>`__
type. The user can add credentials for the ICE server depending on the
server setup.

There are public STUN and TURN servers which can be used by any user. In
fact the Web Conferencing add-on comes with a default STUN server.

In production environments, it is highly recommended to use a dedicated
ICE server which is not the default one,as it produces warnings in the
platform logs.

 .. note:: 	* Configuring an ICE server for WebRTC is optional as it falls back to
			"peer-to-peer" connectivity, but this will not work well accross
			networks.

			* WebRTC allows you to specify multiple STUN/TURN servers which can be
			optionally secured with credentials. The ICE protocol will use this
			list of servers to help with WebRTC peers connectivity.

Here are some examples of STUN/TURN servers which can be used to
configure your WebRTC:

* `XIRSYS <https://xirsys.com/>`__

* `Coturn <https://github.com/coturn/coturn/wiki/Downloads>`__

.. |image0| image:: images/webconf/admin_interface.png
.. |image1| image:: images/webconf/admin_menu.png
.. |image2| image:: images/webconf/admin_interface_access.png
.. |image3| image:: images/webconf/enable_disable.png
.. |image4| image:: images/webconf/settings_button.png
.. |image5| image:: images/webconf/webRTC_settings.png
.. |image6| image:: images/webconf/plus_button.png
