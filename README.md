# FM-UseHttpProtocol
 
There is a setting FileMaker 21.1 that allows you to set a preference for setting the network protocol to use. If the FileMaker Server you are connecting to is configured to use HTTPS Tunneling, all traffic to the FileMaker Pro client will use port 443 instead of the default 5003 that uses TCP/IP. In FileMaker Pro you can manually set this in the Preferences.

This can be used to copy the scripting into your own file, depending on what suites your application and deployment. Reference the scripting in the file to set the value as you see fit. You might also reference the scripting, either powershell on Windows or Applescript on Mac to set this preference on client machines as needed. 

If FileMaker Pro is currently running, a restart will be required before applying the setting. Otherwise, the setting will be applied for the next launch. Note that changing the setting in FileMaker Server will also require a restart of the service.
