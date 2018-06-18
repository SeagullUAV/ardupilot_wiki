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

`Seagull #MAP2 <https://www.seagulluav.com/product/seagull-map2/>`__ provides
everything needed to connect a Pixhawk with one of the 300+ supported cameras in order to automate camera shutter triggering. 

   #MAP2 from Seagull UAV

.. figure:: https://www.seagulluav.com/wp-content/uploads/2016/03/SMAP-1100_01-570x570.png

#MAP2 supports two trigger modes: 

"AF-T" (Autofocus-Trigger, 1 sec pre-AF then trigger)
"IS-T" (Instant-Trigger, instant trigger as soon as camera locks focus).

Furthermore a "Timelapse" (intervalometer) mode is also available.
Sony "MULTI" interfaced cameras can also supports a "Camera on/off" feature.

**NOTE**: An updated camera compatibility list can always be found on the `#MAP2 Cable finder page <https://www.seagulluav.com/map2-cable-finder/>`.  

:ref:`Camera triggering using Seagull #MAP2 <common-camera-shutter-triggering-for-sony-multiport-connectors-using-seagull-map>` provides a brief overview of how to set up the #MAP2 unit. 
Additional info can be found on the `#MAP2 Support page <https://www.seagulluav.com/seagull-map2-support/>`__ and more detailed instructions are provided in the `Seagull #MAP2 Manual <https://www.seagulluav.com/manuals/Seagull_MAP2-Manual.pdf>`__.



Detailed information
====================

.. toctree::
    :maxdepth: 1
    
    Seagull #MAP2 (UAV camera trigger) <common-camera-shutter-triggering-for-sony-multiport-connectors-using-seagull-map>
