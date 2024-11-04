Move Window
===========

Category
--------
Window Commands

Description
-----------

This command moves a window to a specified location on screen. Use this command when you want to move an existing window by name to a certain point on the screen.

Parameters
----------

**Window Name**
	Indicate or select the window that you want to move.

**Window X Position**
	Indicate the new X horizontal coordinate (pixel) for the window's location. 0 starts at the left of the screen and goes to the right. This number is the pixel location on screen.Maximum value should be the maximum value allowed by your resolution.For 1920x1080, the valid range could be 0 - 1920.

**Window Y Position**
	Indicate the new Y vertical coordinate (pixel) for the window's location. 0 starts at the top and goes downwards. This number is the pixel location on screen. Maximum value should be the maximum value allowed by your resolution. For 1920x1080, the valid range could be 0-1080.



Returned Value
--------------
	This command does not have returned value.

Example Usage
-------------

	Example Location:  
		`BYpass\\Examples\\Window Commands\\Move Window\\Move Window.xml`

See Also
--------
	- :doc:`Activate Window <activatewindow>`
	- :doc:`Close Window <closewindow>`
	- :doc:`Resize Window <resizewindow>`
	- :doc:`Set Window State <setwindowstate>`
	- :doc:`Wait For Window To Exist <waitforwindow>`

	
