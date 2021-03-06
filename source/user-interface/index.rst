User Interface
==============

Eureka features a 2D orthogonal view and a 3D view. Switch between the two views with the :kbd:`tab` key.

.. image:: 2d-view.png

*The 2D view is used to construct walls and place things on the map*

.. image:: 3d-view.png

*The 3D view is used to preview textures and make ceiling, floor and light adjustments*

Panning and Zooming
-------------------

To move around the 2D view:

* Roll the mouse wheel to zoom
* Click and drag with the middle mouse button (mouse wheel) to pan
* Press :kbd:`home` to zoom the whole map into view

The Camera
----------

This arrow in 2D view indicates the current position of the 3D camera.

* Press :kbd:`'` (single quote) in the 2D view to position the 3D camera at the location of the mouse cursor.
* Press :kbd:`end` in 2D view to center the map on the camera position.

.. image:: camera.png

When in the 3D view you can control camera movement with the following controls:

* Roll the mouse wheel to move forward/backward
* Click and drag left/right with the middle mouse button to rotate the view
* Click and drag up/down with the middle mouse button to raise/lower the view

The Grid
--------

Toggle the grid in 2D view with the **Grid** dropdown box (located on the bottom status bar), or by pressing :kbd:`g`. You can quickly change the grid size with the :kbd:`0-9` keys.

Toggle free mode / grid snapping with the :kbd:`f` key.

.. image:: 2d-grid.png

.. note::

    If you encounter lag while panning a large zoomed-out map, disable grid rendering with :kbd:`g` while panning.

Rendering Mode
--------------

The `View / Sector Rendering` menu toggles how the 2D view draws sectors.

.. image:: sector-rendering-menu.png

Floors
^^^^^^

This mode draws the floor textures of sectors.

.. image:: sector-rendering-floors.png

Ceilings
^^^^^^^^

This mode draws the ceiling textures of sectors.

.. image:: sector-rendering-ceilings.png

Lighting
^^^^^^^^

The light render mode draws shades of sector light levels.

.. image:: sector-rendering-lighting.png

Sound
^^^^^

The sound render mode highlights sectors based on how sound travels. You have to be in sector edit mode for this mode to work (press :kbd:`s`), hover your mouse cursor over a sector to see how sound will propagate.

* Orange sectors indicate where sound will reach at volume 2
* Blue sectors indicate connected sectors where sound does not reach
* Red sectors indicate where sound will reach at volume 1

By setting the `sound block` flag on linedefs, you can lower the volume of traveling sounds. Sounds do not travel across two sound-blocking lines.

.. image:: sector-rendering-sound.png


Find and Replace
----------------

Open the find panel with the `View / Find` menu or press :kbd:`control-f`.

You can search for Things, line textures, sector flats, lines by type (specials) or sectors by type.

.. image:: find-panel.png
