Execute DLL
===========

Category
--------
API Commands

Description
-----------

This command called function from external DLL file. Use this command to execute external function in a DLL file.

Parameters
----------

**DLL file path**
	Path to the DLL file

**Class Name**
	The name of the class that contains the method to be invoked. Provide the parent class name in the DLL.

**Method**
	The name of the method in the class to invoke. Provide the method name in the DLL to be invoked.

**Parameters**
	The parameters corresponding to the method (if required) 

	.. note::

	   It doesn't necessary to manully enter **Class Name**, **Method** These value will be automatically populated during **DLL file path** is specified.


Returned Value
--------------

**Result**
	The variable to receive the result.

Example Usage
-------------

	Example Location:  
		`BYpass\\Examples\\API Commands\\Execute DLL\\Execute DLL.xml`

See Also
--------
	- :doc:`Execute REST API <rest>`
	- :doc:`HTTP Request <httprequest>`
	- :doc:`HTTP Result Query <httpqueryresult>`	
