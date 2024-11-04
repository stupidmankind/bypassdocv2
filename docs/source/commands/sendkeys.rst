Send Keystrokes
===============

Category
--------
Input Commands

Description
-----------

Sends keystrokes to a targeted window. Use this command when you want to send keystroke inputs to a window.

Parameters
----------

**Window Name**
	Select the window that you want to activate

**Text**
	Enter the text that should be sent to the specified window. If the text contains +,^,%,~,(,) character, please put it inside {}. For example. \"5{+}4=\". Special keys can be sent suchas {ENTER}, {F1}, etc. For more information, please visit https://docs.microsoft.com/en-us/dotnet/api/system.windows.forms.sendkeys?redirectedfrom=MSDN&view=windowsdesktop-6.0

**Encryption**
	Indicate if the text in 'TextToSend' is Encrypted.



Returned Value
--------------
	This command does not have returned value.

Example Usage
-------------

	Example Location:  
		`BYpass\\Examples\\Input Commands\\Send Keystrokes\\Send Keystrokes.xml`

See Also
--------
	- :doc:`Prompt for HTML Input <htmlinput>`
	- :doc:`Prompt for Input <userinput>`
	- :doc:`Send Advanced Keystrokes <sendadvancedkeystrokes>`
	- :doc:`Send Hotkey <sendhotkey>`
	- :doc:`Send Mouse Click <sendmouseclick>`
	- :doc:`Send Mouse Move <sendmousemove>`

	
