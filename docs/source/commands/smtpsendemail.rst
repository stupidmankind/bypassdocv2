Send SMTP Email
===============

Category
--------
Email Commands

Description
-----------

This command allows you to send email using SMTP protocol. Use this command when you want to send an email and have access to SMTP server credentials to generate an email.

Parameters
----------

**Host Name**
	The email server host that is to be used, e.g., smtp.gmail.com.

**Port**
	Define the port number that should be used when contacting the SMTP service.

**User Name**
	The username used to send the message.

**Password**
	The password of the email account used to send the message.

**Encrypted Password**
	Select Yes if password is encrypted.

**From Email**
	Specify how the 'From' field should appear, e.g., myRobot@company.com.

**To Email**
	Specify the destination email that should be addressed, e.g., test@test.com.

**Subject**
	The subject of the email message.

**Body**
	The body of the email message.

**Mail Type**
	Select email type you want to send.

**Images**
	The Images to be added to the email message. For multiple images, use comma to separate, e.g., c:\\sales reports\\fy06q4.jpg,c:\\sales reports\\fy06q5.jpg.

**Attachment**
	The attachments to be added to the email message, e.g., c:\\sales reports\\fy06q4.xlsx.

**SSL**
	Indicate if SSL should be used.

**SSL Validation**
	Indicate if SSL should be validated.



Returned Value
--------------
	This command does not have returned value.

Example Usage
-------------

	Example Location:  
		`BYpass\\Examples\\Email Commands\\Send SMTP Email\\Send SMTP Email.xml`

See Also
--------
	- :doc:`Get IMAP Mail <emailimap>`
	- :doc:`Save Attachment <emailsaveattachment>`

	
