Begin If
========

Category
--------
If Commands

Description
-----------

This command is used to make the decision within the script by evaluate the statement. The command under if block will be exeucted if the statement is true.


Parameters
----------

**If Action**
	Indicate the action type of the if command. **Begin If** supports following types of actions.

	+------------------------------+-------------------------------------------------+
	| If Action                    | Description                                     |
	+==============================+=================================================+
	| Value                        | Compare two values |br|                         |
	+------------------------------+-------------------------------------------------+
	| Date Compare                 | Compare two date values                         |
	+------------------------------+-------------------------------------------------+
	| Variable Compare             | Compare two string values                       |
	+------------------------------+-------------------------------------------------+
	| Variable Has Value           | Check if variable has value or not              |
	+------------------------------+-------------------------------------------------+
	| Variable Is Numberic         | Check if variable is numeric or not             |
	+------------------------------+-------------------------------------------------+
	| Window Name Exists           | Check if existing window exists                 |
	+------------------------------+-------------------------------------------------+
	| Active Window Name Is        | Check the name of current active window         |
	+------------------------------+-------------------------------------------------+
	| File Exists                  | Check if file exists                            |
	+------------------------------+-------------------------------------------------+
	| Folder Exists                | Check if folder exists                          |
	+------------------------------+-------------------------------------------------+
	| Custom                       | Write custom using programming literature       |
	+------------------------------+-------------------------------------------------+

**Condition**
	This setting is based on **If Action**. Setting this parameter to compare *Value1* (value on the left) 
	to *Value2* (value on the right) with following operands.
	
	+--------------------------------+--------------------------------------------------+
	| Operand                        | Description                                      |
	+================================+==================================================+
	| is equal to                    | Return true if *Value1* and *Value2* are equal   |
	+--------------------------------+--------------------------------------------------+
	| is not equal to                | Return true if *Value1* and *Value2* are NOT     |
	|                                | equal                                            |
	+--------------------------------+--------------------------------------------------+
	| is greater than                | Return true if *Value1* is greater than *Value2* |
	+--------------------------------+--------------------------------------------------+
	| is greater than or equal to    | Return true if *Value1* is greater than or equal |
	|                                | to *Value2*                                      | 
	+--------------------------------+--------------------------------------------------+
	| is less than                   | Return true if *Value1* is less than *Value2*    |
	+--------------------------------+--------------------------------------------------+
	| is less than or equal to       | Return true if *Value1* is less than or equal    |
	|                                | to *Value2*                                      | 
	+--------------------------------+--------------------------------------------------+
	| contains                       | Return true if *Value2* is a part of *Value1*    |
	+--------------------------------+--------------------------------------------------+
	| does not contain               | Return true if *Value2* is NOT a part of *Value1*|
	+--------------------------------+--------------------------------------------------+
	
	and following flags for **If Action** that does not have *Value2*
	
	+--------------------------------+--------------------------------------------------+
	| Flag                           | Avalilable to Command                            |
	+================================+==================================================+
	| It Has Value |br|              | Variable Has Value                               |
	| It Does Not Have Value         |                                                  |
	+--------------------------------+--------------------------------------------------+
	| It Is Numeric |br|             | Variable Is Numeric                              |
	| It Is Not Numeric              |                                                  |
	+--------------------------------+--------------------------------------------------+
	| It Does Exist |br|             | File Exists / Folder Exists                      |
	| It Does Not Exist              |                                                  |
	+--------------------------------+--------------------------------------------------+

Returned Value
--------------
	This command does not have returned value.


Example Usage
-------------

	Example Location:  
		`BYpass\\Examples\\If Commands\\Begin If\\Begin If.xml`

See Also
--------
	- :doc:`Else <else>`
	- :doc:`End If <endif>`
	- :doc:`Evaluate Statement <evaluatestatement>`
	- :doc:`Statement Operand <statementoperand>`

.. note::

   This command is a block command and always need **End If** command at the end.
	
.. |br| raw:: html

      <br>