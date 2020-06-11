# FM-SetInitialfile
 
There is a setting FileMaker 18 that allows you to set a preference for opening a file when FileMaker is first launched. Previously the only way to set this preference was to specify it in a text document, Assisted Install.txt, when you first installed that application. In FileMaker 19, you can manually set this in the Preferences.

This setting can be quite useful in certain deployment scenarios, such as office wide deployments where your solution should open by default for users. Doing so will avoid users seeing the default FileMaker Launch Center that can be confusing to some users. The file to be opened can either be a local file, or a file hosted on FileMaker Server or FileMaker Cloud.

In another blog post from our friends at Beezwax (https://blog.beezwax.net/2020/06/09/setting-filemaker-startup-file-from-cli/) show how this can be set. They also show how this preference can be set with some command line, depending on if you are running on Windows or Mac.

With that as inspiration, I put together FileMaker file that can set this preference. FileMaker can detect the platform you are running on, either Windows or Mac, and set the appropriate powershell or applescript, respectively.

This can be used to copy the scripting into your own file, depending on what suites your application and deployment. Reference the scripting in the file to set the value as you see fit. 
