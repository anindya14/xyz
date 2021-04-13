Stage1(revmeup) 
	- Reverse Engineer the Binary and find the password (Use any means necessary)

Stage2(StPwner) - Load the OVF file in Virtual Box or VmWare.
	- Use the data found in stage 1 to get access to the Linux Server's custom Service
	- Find the service
	- Exploit the server
	- Get hint/clue on the File System

Stage3(GhostShell)
	- Use the Hint/Clue to get access to the normal user account
	- Elevate privileges to root.