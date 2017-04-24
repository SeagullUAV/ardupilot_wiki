.. _common-camera-shutter-triggering-cables-for-purchase:

=================================================
Camera Shutter Trigger Boards/Cables for Purchase
=================================================

This article provides links to cables/boards that can be used for
triggering the camera shutter from ArduPilot.

Overview
========

ArduPilot allows you to :ref:`configure a servo or relay output as the control signal for the camera shutter <common-camera-shutter-with-servo>` so that it can be used in
:ref:`Camera Missions <common-camera-control-and-auto-missions-in-mission-planner>`.
Additional hardware is required to convert the shutter activation signal
to the format expected by the particular camera.

This article contains links to information about camera cables and
boards that can be used for this purpose.

.. tip::

   Please add new boards/cables you discover to this page (or `request the addition <https://github.com/ArduPilot/ardupilot_wiki/issues/new>`__).

Seagull #MAP2
=============

`Seagull #MAP2 <http://www.seagulluav.com/product/seagull-map2/>`__ provides everything needed to connect a Pixhawk or APM controller to any of the 350+ supported camera models. 

.. figure:: http://www.seagulluav.com/ardupilot/SeagullMAP2.jpg
   :target: http://www.seagulluav.com/ardupilot/SeagullMAP2.jpg

#MAP2 supports two primary trigger modes: 

- AF-T (Autofocus-Trigger, 1 sec pre-AF then trigger)
- IS-T (Instant-Trigger, instant trigger as soon as camera locks focus)

_On Sony "Multi" cameras it also supports turning the camera On/Off._


#MAP-X is controlled by a standard PWM servo signal that intergrates perfectly with Pixhawk and APM controllers.

**Both camera cable and servo cables are included with #MAP2.**


Supported camera brands:

- Canon
- Nikon
- Sony
- Apple
- Contax
- Fujifilm
- Hasselblad
- Leica
- Olympus
- Panasonic
- Pentax
- Samsung
- Sigma

The updated list of compatible cameras are easiest viewed on the `Seagull #MAP2 product page <http://www.seagulluav.com/product/seagull-map2/>`__ from the dropdown boxes at the top of the page.

Seagull #MAP2 also adds timelapse (interval) triggering, able to trigger at 1, 2, 3, 4, 5, 10, 15 or 20sec interval.
It even features a Sony QX-1 "keep-alive" mode to prevent the know "auto power-off" after 2min on the QX-1.


More detailed instructions are provided in the `Seagull #MAP2 Manual <http://www.seagulluav.com/manuals/Seagull_MAP2-Manual.pdf>`__.

Seagull UAV is known for their superior support - be sure to contact them if the above _"triggers"_ any questions !

-  `Purchase Seagull #MAP2 <http://www.seagulluav.com/product/seagull-map2/>`__


Seagull #MAP-X
==============

`Seagull #MAP-X <http://www.seagulluav.com/product/seagull-map-x/>`__ gives you precise coordinates of photographs taken and only tags the location if the photograph has been successfully taken. On top of that #MAP-X outputs coordinates of failed photographs, giving you a quick data for re-flying survey points and capture the missing photos.

As well as the above #MAP-X also generates a .KML file for each flight with all of the “Confirmed” and “Failed” coordinates of photos, which can be loaded into Google Earth for a quick overview after each flight !

.. figure:: http://www.seagulluav.com/ardupilot/SeagullMAPX.jpg
   :target: http://www.seagulluav.com/ardupilot/SeagullMAPX.jpg

With Seagull #MAP-X you get everything you need to connect your camera to your Pixhawk or APM controller.
Hotshoe adaptor, servo and camera cables are included, as well as the GPS antenna, microSD card etc. – making it a Plug&Play solution !
#MAP-X delivers unbelievable value to your professional mapping jobs, saving both you and your clients time and money, so you can do more jobs in a day.

Supported camera brands:

- Canon
- Nikon
- Sony
- Fujifilm
- Leica
- Olympus
- Panasonic
- Samsung
- Sigma

The updated list of compatible cameras are easiest viewed on the `Seagull #MAP-X product page <http://www.seagulluav.com/product/seagull-map-x/>`__ from the dropdown boxes at the top of the page.

Seagull #MAP-X also features a user-defined timelapse (interval) trigger, that can be set to match the needs of the application.

More detailed instructions are provided in the `Seagull #MAP-X Manual <http://www.seagulluav.com/manuals/Seagull_MAP-X-Manual.pdf>`__.

Seagull UAV is known for their superior support - be sure to contact them if the above _"triggers"_ any questions !

-  `Purchase Seagull #MAP-X <http://www.seagulluav.com/product/seagull-map-x/>`__

Detailed information
====================

.. toctree::
    :maxdepth: 1
    
    Seagull #MAP2 <common-camera-shutter-triggering-for-sony-multiport-connectors-using-seagull-map>
