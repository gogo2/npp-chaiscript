# npp-chaiscript


####Installation (based on [wiki](http://docs.notepad-plus-plus.org/index.php/User_Defined_Language_Files))
1. Choose appropriate .xml file or files (based on your theme preferences)
2. If you don't have an userDefineLang.xml file already, you can drop this file among your other configuration file, in the Notepad++ Install Folder. It should be named userDefineLang.xml.
  * It was reported that "creating the XML file in C:\Program Files (x86)\Notepad++ on 64-bit Windows 7 didn’t add the syntax highlighting to notepad++. I had to move the XML file to <user>\AppData\Roaming\Notepad++ for it to work."
3. Otherwise, open both the existing and new file.
  1. Select all of the new file, copy, and paste at the end of the current file.
  2. This will have created a spurious </Notepad_Plus><Notepad_plus> pair i the middle, each tag on a line by itself. Remove these two consecutive lines.
  3. Close Notepad++.
  
Your Languages menu will show the newly added language at the bottom, next time you launch Notepad++.