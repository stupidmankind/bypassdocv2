Image Recognition
=================

Category
--------
Image Commands

Description
-----------

This command attempts to find an existing image on screen. Use this command when you want to attempt to locate an image on screen.  You can subsequently take actions such as move the mouse to the location or perform a click.  This command generates a fingerprint from the comparison image and searches for it in on the desktop.

Parameters
----------

**Image Capture**
	The image will be used as the image to be found on screen.

**Offset X Coordinate**
	Specify if an offset is required. 0 or 100. This will move the mouse X pixels to the right of the location of the image.

**Offset Y Coordinate**
	Specify if an offset is required. 0 or 100. This will move the mouse Y pixels down from the top of the location of the image.

**Similarity**
	Specify the similarity threshold between 0.0 - 1.0 to find the image.

**Actions**
	Please indicate an action type if required.



Returned Value
--------------
	This command does not have returned value.

Example Usage
-------------

	Example Location:  
		`BYpass\\Examples\\Image Commands\\Image Recognition\\Image Recognition.xml`

See Also
--------
	- :doc:`Perform OCR <ocr>`
	- :doc:`Take Screenshot <screenshot>`

	
